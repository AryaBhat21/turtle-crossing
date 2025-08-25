# Turtle Crossing Game

A simple arcade-style game built with Python's `turtle` graphics module. Help the turtle cross the road while avoiding moving cars. Each successful crossing increases the level and the speed of the cars!

## How to Play

- Run `main.py` to start the game.
- Use the **Up Arrow** key to move the turtle forward.
- Dodge the cars and reach the top of the screen to advance to the next level.
- The game ends if the turtle collides with a car.

## Features

- Increasing difficulty: Cars move faster with each level.
- Scoreboard displays the current level.
- "Game Over" message when you lose.

## Requirements

- Python 3.7+
- No external dependencies (uses only the standard library).

## File Structure

- `main.py` — Game loop and event handling
- [`player.py`](player.py) — Player (turtle) logic
- [`car_manager.py`](car_manager.py) — Car creation and movement
- [`scoreboard.py`](scoreboard.py) — Scoreboard display

## How to Run

1. Make sure you have Python installed.
2. Open a terminal in the project directory.
3. Run:

   ```sh
   python main.py
   ```

Enjoy
