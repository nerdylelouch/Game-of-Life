# Game of Life - C++ Implementation

## Overview

The "Game of Life" is a cellular automaton devised by British mathematician John Horton Conway in 1970. This program provides a simple implementation of Conway's Game of Life in C++. The universe of the Game of Life is an infinite two-dimensional grid of cells, each of which can be either alive or dead. The game evolves over discrete time steps according to a set of rules that determine the state of each cell based on its neighbors.

## Features

- **Grid Initialization**: You can set up the initial state of the grid either manually by entering cell coordinates or by reading from a file.
- **Game Rules**:
  - Any live cell with fewer than two live neighbors dies (under-population).
  - Any live cell with two or three live neighbors lives on to the next generation.
  - Any live cell with more than three live neighbors dies (over-population).
  - Any dead cell with exactly three live neighbors becomes a live cell (reproduction).
- **Display**: The grid is displayed with 'O' representing live cells and '.' representing dead cells.
- **Cross-Platform Compatibility**: Supports Windows, Linux, and macOS.

## Compilation

To compile the code, use the following command:

```bash
g++ -o game_of_life game_of_life.cpp
```
**Run and start the Game**: After setting up the grid, choose to start the game by entering 'y' or 'Y'. The game will then continuously update and display the grid according to the rules.
**Terminate**: To stop the game, simply close the terminal or interrupt the process.
## File Format
When reading from a file, the file should contain pairs of integers (x and y coordinates) on separate lines. For example:
```bash
1 2
3 4
5 6
```
## Screen Clearing
The screen is cleared at each step to refresh the display. This implementation supports different methods for clearing the screen depending on the operating system.

## Example
Here is a brief example of running the program:

