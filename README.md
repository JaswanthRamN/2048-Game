# 2048 Game

A Python implementation of the popular 2048 game using Pygame.

## Requirements
- Python 3.x
- Pygame

## Installation
1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## How to Play
1. Run the game:
```bash
python game.py
```

2. Use arrow keys to move tiles:
- ↑ (Up Arrow): Move tiles up
- ↓ (Down Arrow): Move tiles down
- ← (Left Arrow): Move tiles left
- → (Right Arrow): Move tiles right

3. Combine matching numbers to create larger numbers
4. Try to reach the 2048 tile!

## Game Rules
- When two tiles with the same number touch, they merge into one tile with the sum of their values
- After each move, a new tile with a value of 2 or 4 appears
- Game ends when you either reach 2048 or can't make any more moves
