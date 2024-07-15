# Snake Game

This is a simple Snake Game implemented in Python using the Pygame library. The player can control the snake's speed through an initial menu.

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/tarunvaid/snake_game.git
    cd snake-game
    ```

2. **Install Pygame**:
    Make sure you have Python installed. Then, install Pygame using pip:
    ```sh
    pip install pygame
    ```

## How to Play

1. **Run the game**:
    ```sh
    python snake_game.py
    ```

2. **Control the snake**:
    - Use the arrow keys to control the direction of the snake.
    - The objective is to eat the green food blocks. Each time the snake eats a food block, it grows longer.

3. **Game Over**:
    - The game ends if the snake runs into the screen border or itself.
    - After game over, press `C` to play again or `Q` to quit.

## Code Overview

### Main Files

- `snake_game.py`: The main game file containing all the game logic and menu for speed selection.

### Functions

- `our_snake(snake_block, snake_List)`: Draws the snake on the screen.
- `message(msg, color, position)`: Displays messages on the screen.
- `gameLoop(snake_speed)`: The main game loop handling the gameplay.
- `mainMenu()`: Displays the initial menu for selecting the snake speed.

## Acknowledgements

- Thanks to the Pygame community for their helpful tutorials and documentation.

