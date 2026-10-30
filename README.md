# Maze Project

A 3D maze exploration game written in C using **raycasting** to render a three-dimensional view from a two-dimensional map. Built as part of the ALX Software Engineering programme.

## Features

- Raycasting-based maze rendering
- Map-driven game environment
- SDL2 graphics and image handling
- C implementation with a Makefile build

## Technologies

- **Language:** C
- **Graphics:** SDL2, SDL2_image
- **Build:** GCC, Make
- **Math:** C math library (`libm`)

## Project Structure

```text
Maze-Project/
├── headers/       # Header files
├── pics/          # Image assets
├── src/           # C source files
├── game_map.map   # Maze map
└── makefile       # Build instructions
```

## Build

Install GCC, Make, SDL2, and SDL2_image development libraries, then run:

```bash
make
```

The Makefile compiles the source files into an executable named `maze`.

## Explore the Code

- [`src/`](src/) — game implementation
- [`headers/`](headers/) — declarations and shared definitions
- [`game_map.map`](game_map.map) — maze layout
- [`makefile`](makefile) — compilation configuration
