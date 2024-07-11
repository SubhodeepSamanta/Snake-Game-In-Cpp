# Snake-Game-In-Cpp

A console-based Snake game implemented in C++ using the Windows API for input handling and screen clearing.

## Overview

This project is a classic Snake game where the player controls a snake that moves around the screen, eating food (represented by 'F') to grow in length. The game ends if the snake runs into itself or the screen boundary. The score increases as the snake eats more food.

## Features

- **Snake Movement**: Control the snake's direction using 'W', 'A', 'S', 'D' keys for Up, Left, Down, and Right respectively.
- **Food (F)**: Food spawns randomly on the screen. Each time the snake eats food, it grows longer, and the score increases.
- **Game Over**: The game ends if the snake collides with itself or the screen boundary.
- **Score Tracking**: Displayed on the screen to keep track of the player's progress.

## How to Play

1. Run the executable.
2. Use 'W', 'A', 'S', 'D' keys to control the snake's direction.
3. The snake moves continuously in the chosen direction.
4. Eat the food ('F') to grow longer and increase your score.
5. Avoid running into the snake's own body or the screen boundary.
6. The game ends when the snake collides, and your score is displayed.

## Project Structure

- **Main Game Loop**: Implements the game logic including snake movement, food generation, collision detection, and score tracking.
- **Input Handling**: Uses `_kbhit()` and `_getch()` from `<conio.h>` for keyboard input.
- **Screen Drawing**: Uses `system("cls")` for screen clearing and console output to draw the game board.

## Getting Started

### Prerequisites

- Windows OS
- C++ compiler with Windows API support (e.g., Visual Studio, MinGW)

## Contributing
If you'd like to contribute to the project, please follow the guidelines outlined in the CONTRIBUTING.md file.

## License
This project is licensed under the MIT License.
