# Alien Invasion Game

## Overview

Alien Invasion is a 2D shooting game built with Python's Pygame library. The player controls a spaceship that can move horizontally and shoot bullets upward. The goal is to shoot down a fleet of aliens invading from the top of the screen.

## Features
- Horizontally movable spaceship controlled by arrow keys.
- Ability to shoot bullets with spacebar.
- Fleets of aliens that drop down and change direction.
- Scoring system with high-score tracking.
- Levels of increasing difficulty.

## Requirements
- Python 3.x
- Pygame
- json (for storing high score)

## Installation

1. Clone this repository.
   ```
   git clone https://github.com/YourUsername/AlienInvasion.git
   ```
2. Install Pygame.
   ```
   pip install pygame
   ```

## Running the Game

Navigate to the directory where the game is located and run:
```
python main.py
```

## Gameplay Controls

- **Right Arrow**: Move spaceship to the right.
- **Left Arrow**: Move spaceship to the left.
- **Spacebar**: Shoot bullets.
- **Q**: Quit the game.

## Files

- `main.py`: Main driver of the game.
- `settings.py`: Contains settings for the game like screen size, bullet speed, etc.
- `game_stats.py`: Keeps track of game statistics.
- `scoreboard.py`: Handles the game's scoring system.
- `button.py`: For creating buttons in the game.
- `ship.py`: Contains the Ship class.
- `bullet.py`: Contains the Bullet class.
- `alien.py`: Contains the Alien class.

## Future Enhancements

- Add power-ups.
- Implement multiplayer functionality.
