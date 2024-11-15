# Snake Game in Python

A simple Snake game built using Python and the Turtle graphics library. The game allows players to control the snake to eat food, grow longer, and avoid collisions with walls or the snake's own tail.

## Features
- **Snake Movement**: Use arrow keys (Up, Down, Left, Right) to control the snake.
- **Food Collection**: Eating food grows the snake's length.
- **Collision Detection**: Resets the game when the snake hits the wall or its own tail.
- **Score Tracking**: Displays the current score and highest score ever achieved.
- **High Score Persistence**: The highest score is saved in `data.txt`, which persists across game sessions.

## Files Description
- `main.py`: The main game loop and logic for snake movement, collision detection, and score management.
- `snake.py`: Defines the Snake class for handling the snake’s body and movement.
- `food.py`: Defines the Food class to generate food at random positions for the snake to consume.
- `scoreboard.py`: Manages the score display and updates the high score stored in `data.txt`.
- `data.txt`: A text file used to store the highest score achieved across all game sessions.

## Setup and Installation

1. **Install Python 3.x**: 
   Make sure you have Python 3.x installed on your system. You can download it from [here](https://www.python.org/downloads/).

2. **Clone or Download the Repository**: 
   - Clone this repository or download the project files to your computer.

3. **Run the Game**:
   Open a terminal or command prompt, navigate to the directory containing the files, and run the game by executing:

   ```bash
   python main.py
   
## How to Play
- **Move the Snake**: Use the arrow keys to navigate the snake.
  - **Up Arrow**: Move the snake up.
  - **Down Arrow**: Move the snake down.
  - **Left Arrow**: Move the snake left.
  - **Right Arrow**: Move the snake right.

- **Game Over**: The game ends when:
  - The snake collides with the wall.
  - The snake runs into its own tail.

When the game is over, the current score resets, and the highest score is updated in `data.txt`.

## Dependencies

- Python 3.x

No additional libraries or frameworks are required for this project. It runs entirely using basic Python functionality.

## Contributions

Feel free to fork this repository, improve it, and submit a pull request. Suggestions for improvement are welcome!


