# Tic-Tac-Toe AI

This project implements a **Tic-Tac-Toe game** with an AI opponent using the Minimax algorithm. The game has a graphical interface powered by OpenCV and features a basic AI that ensures challenging gameplay.

## Features

- **Single-player Mode**: Play against the AI, which uses the Minimax algorithm to make optimal moves.
- **Graphical Interface**: Display game state, score, and moves using OpenCV.
- **Dynamic Reset**: Reset the game state at any time.
- **Customizable Colors and Dimensions**: Modify game visuals with predefined attributes.
- **AI Behavior**: The AI adapts based on the player's selection of 'X' or 'O'.

## Prerequisites

- Python 3.x
- Required libraries:
  - `numpy`
  - `opencv-python`
  - `pickle`

## Screenshots
![Screenshot 2025-01-16 164416](https://github.com/user-attachments/assets/92d2ce45-3ac5-4ddd-872d-b8d461019d1a)

![Screenshot 2025-01-16 154429](https://github.com/user-attachments/assets/430cd645-a73c-411f-89fb-d53ec3c6795f)

![Screenshot 2025-01-16 164232](https://github.com/user-attachments/assets/d66ac704-746c-4d7b-86ba-47de89f9449c)


Install the dependencies using pip:
```bash
pip install numpy opencv-python
How to Run
Clone this repository or download the script TicTacToeAI.py.
Run the script:
bash
Copy
Edit
python TicTacToeAI.py
The game window will open. Follow these controls:
Use your mouse to select a grid cell for your move.
Press q to quit the game.
How It Works
The Minimax Algorithm is used to determine the best possible moves for the AI. It evaluates game states recursively to maximize AI outcomes while minimizing player advantage.
The game alternates between player and AI moves until the board is full or a win condition is met.
The scores are displayed in the game window, and you can reset or quit anytime.
File Structure
TicTacToeAI.py: Main script containing the game logic and AI implementation.


