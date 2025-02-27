# Block Tower Tactics

This is a simple implementation of the classic Tetris game using Python's Tkinter library for the GUI and the Pillow library for handling images. The game features colorful Tetromino shapes and user controls for moving and rotating the pieces as they fall toward the bottom of the board.

## Features

- Classic Tetris gameplay mechanics
- Colorful Tetromino shapes
- Scoring system
- Background image
- Responsive controls using keyboard input

## Prerequisites

Before running the game, ensure you have the following:

1. **Python Installed**: Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

2. **Pillow Library**: You will need the Pillow library to handle images. You can install it using pip:

   ```markdown
   pip install Pillow
   ```

3. **Press Start 2P Font**: This game uses the **Press Start 2P** font for displaying text. You must install the font on your system; otherwise, the game may not display text properly. You can download the font from neither of these steps:

   - [Press Start 2P Font](https://fontmeme.com/fonts/press-start-2p-font/)
   - The font presented in the font folder.

   After downloading, install the font by following your operating system's font installation instructions.

## Changing The Background
 Changing the background is as easy as pie 
 
- Place your background in the bg folder and call it whatever (You can just set it as bg1.jpg)
- Open the code in an editor (Notepad++ or just classic Notepad)
- Underneath, find bg0.jpg and edit to the bg\yourimagename.jpg

There you have it, you changed the background.

## Running the Game

1. After ensuring all dependencies are installed and the font is added to your system, download or clone this repository.

   ```markdown
   git clone https://github.com/vmprs/Block-Tower-Tactics.git
   ```

3. Navigate to the directory where the game files are located.

4. Run the game by clicking the .pyw script.

## Controls

- **Arrow Keys**: Move the falling Tetromino left, right, or down.
- **Up Arrow**: Rotate the Tetromino clockwise.
- **R Key**: Rotate the Tetromino counterclockwise.
- **Restart Button**: Click this button to restart the game after it ends.

## Gameplay

The objective of the game is to manipulate falling Tetromino shapes by moving them sideways and rotating them. The goal is to form complete rows on the game board. When a row is filled, it clears out, and points are awarded. The game continues until the player can no longer place new Tetrominoes on the board.

Enjoy playing Tetris!
```
