# Ping-Pong-Game
This is a simple implementation of the classic Pong game using Python's Turtle graphics library. The game consists of two paddles and a ball, and the objective is to bounce the ball back and forth between the paddles without letting it pass.

## Files

- `main.py`: The main script to run the Pong game.
- `scoreboard.py`: A Python module for keeping score.
- `paddle.py`: A Python module for creating paddles.
- `ball.py`: A Python module for creating the ball.

## How to Play

1. Run `main.py` to start the Pong game.
2. Use the following controls:
   - Right Paddle (Player 1):
     - Move up: Up arrow key
     - Move down: Down arrow key
   - Left Paddle (Player 2):
     - Move up: 'W' key
     - Move down: 'S' key
3. The game continues until you decide to exit by clicking anywhere on the game window.

## Code Files

### `main.py`

This is the main script that sets up the game, creates the game objects, and manages the game loop.

### `scoreboard.py`

This module handles the game's scorekeeping. It displays the scores of both players on the screen.

### `paddle.py`

This module defines the Paddle class, which represents the paddles used by players in the game. It allows paddles to move up and down on the screen.

### `ball.py`

This module defines the Ball class, which represents the ball used in the game. It handles the ball's movement, bouncing off walls and paddles, and resetting its position.
