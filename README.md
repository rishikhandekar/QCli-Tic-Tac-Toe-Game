# Tic-Tac-Toe

 Check this out! 👇 I leveraged Amazon Q CLI with a simple prompt to instantly generate a complete, classic two-player Tic-Tac-Toe game in Python using Pygame.

 ## Features

 - **Clean, Visual Interface**: 3x3 grid with clear X and O markers
 - **Two-Player Gameplay**: Take turns with a friend on the same computer
 - **Win Detection**: Automatically detects winning combinations (rows, columns, diagonals)
 - **Draw Detection**: Identifies when the game ends in a draw
 - **Game Status Display**: Shows whose turn it is and game results
 - **Easy Restart**: Reset the game with a button click or keyboard press

 ## Requirements

 - Python 3.x
 - Pygame library

 ## Installation

 1. Clone this repository:
    ```
    git clone https://github.com/rishikhandekar/QCli-Tic-Tac-Toe-Game
    ```

 2. Install the required dependencies:
    ```
    # Using pip
    pip install pygame

    # Or using apt on Debian/Ubuntu
    sudo apt-get install python3-pygame
    ```

 ## How to Play

 1. Run the game:
    ```
    python3 tic_tac_toe.py
    ```

 2. Game Rules:
    - Players take turns placing their mark (X or O) on the board
    - Player X always goes first
    - Click on an empty square to place your mark
    - Get three of your marks in a row, column, or diagonal to win
    - If all squares are filled with no winner, the game ends in a draw

 3. Controls:
    - **Mouse Click**: Place your mark on the board
    - **R Key**: Reset the game at any time
    - **Play Again Button**: Appears after a game ends


 ## Games Video

 [I Build a Tic-Tac-Toe Game with Amazon Q CLI | Build Games with Amazon Q CLI](https://youtu.be/h6l0PJ-4-5M?si=lG_IMtyhVrGxo4u_&t=527)

 ## Code Structure

 The game is contained in a single Python file (`tic_tac_toe.py`) and uses the following components:

 - **Pygame Setup**: Initializes the game window and basic settings
 - **Game Board**: Manages the 3x3 grid and game state
 - **Drawing Functions**: Renders the grid, X's, O's, and status messages
 - **Input Handling**: Processes mouse clicks and keyboard input
 - **Game Logic**: Checks for wins, draws, and manages player turns
 - **Reset Functionality**: Allows starting a new game

 ## Customization

 You can easily customize the game by modifying these variables at the top of the script:

 - `WIDTH`, `HEIGHT`: Change the window dimensions
 - `LINE_WIDTH`: Adjust the thickness of grid lines
 - `BOARD_SIZE`: Change the grid size (though win logic is designed for 3x3)
 - `CIRCLE_RADIUS`, `CIRCLE_WIDTH`, `CROSS_WIDTH`: Modify the appearance of X's and O's
 - Color constants: Change the game's color scheme

 ## License

 This project is licensed under the MIT License - see the LICENSE file for details.

 ## Acknowledgments

 - Built with [Pygame](https://www.pygame.org/)
 - Inspired by classic Tic-Tac-Toe gameplay

 ## Contributing

 Contributions are welcome! Please feel free to submit a Pull Request.

 1. Fork the repository
 2. Create your feature branch
 3. Commit your changes
 4. Push to the branch
 5. Open a Pull Request
