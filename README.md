# Chess Engine in Python

This is a simple and efficient chess engine implemented entirely in Python. It allows users to play chess against the computer, using an AI based on a Minimax algorithm with Alpha-Beta pruning for decision-making. The engine is designed to be easy to understand, extend, and play against the computer.

## Features

- **Minimax Algorithm**: Uses Minimax search with Alpha-Beta pruning to decide on optimal moves.
- **Piece Evaluation**: A basic evaluation function based on material balance, piece positions, and basic board control.
- **Move Generation**: Generates legal moves for all chess pieces, including special moves like castling and en passant.
- **Endgame Detection**: Detects checkmate, stalemate, and draw conditions.
- **Game History**: Keeps track of moves made during the game.

## Prerequisites

Make sure you have Python 3.6 or later installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

### Install Dependencies

If your project uses any third-party libraries, you can list them in a `requirements.txt` file. If you don't have one, you can manually install the required packages using `pip`. For example:

```bash
pip install numpy
pip install pygame
