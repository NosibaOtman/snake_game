# Snake Game

A classic Snake game implemented in Python. The game features interactive gameplay, including a snake that moves on a grid, collects apples to grow, and avoids bombs that explode after a set time.

## Features

- Snake movement in four directions (Up, Down, Left, Right)
- Randomly spawning apples with score values
- Bombs with explosion radius that appear and explode over time
- Dynamic game board using `GameDisplay` for graphical rendering
- Collision detection (self-collision, walls, bombs)
- Score tracking

## Files

- `snake_main.py` – Main game logic and loop  
- `game_display.py` – Handles the drawing of the game board (do not modify)  
- `game_parameters.py` – Contains constants and random object generators (apples and bombs)  

## How to Run

1. Make sure Python 3.x is installed  
2. Run the game with:  
```bash
python snake_main.py
