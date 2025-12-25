# Ludo Game

## Project Timeline
- 📅 **Originally developed and completed:** July 2023 (Course Project, NED University)
- 📤 **Uploaded to GitHub:** December 2025

A C++ implementation of the classic Ludo board game using SFML for graphics and user interface.

## Features

- Classic Ludo gameplay
- Graphical user interface
- Player selection
- Dice rolling mechanics
- Game board and piece movement

## Prerequisites

- C++ compiler (e.g., g++, MinGW)
- SFML 2.4.0 or later
- Windows/Linux/MacOS

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd ludo-game
   ```

2. Install SFML:
   - Download SFML from [official website](https://www.sfml-dev.org/download.php)
   - Follow installation instructions for your platform

3. Build the project:
   - On Windows with MinGW:
     ```
     g++ src/main.cpp -o ludo-game -lsfml-graphics -lsfml-window -lsfml-system
     ```
   - Or use your preferred build system
   - Adjust compiler flags as needed for your setup

## Usage

Run the executable:
```
./ludo-game
```

## Screenshots

### Menu
![Menu](Screenshots/Menu.jpg)

### Loading Screen
![Loading](Screenshots/Loading.jpg)

### Player Selection
![Player Selection](Screenshots/Player%20Selection%20Menu.jpg)

### Actual Game
![Actual Game](Screenshots/Actual%20Game.jpg)

## Project Structure

- `src/` - Source code files
- `fonts/` - Font files
- `images/` - Image assets
- `assets/` - Audio files and other resources
- `Screenshots/` - Game screenshots
- `UML PHOTOS/` - UML diagrams
- `docs/` - Documentation and reports

## Contributing

This is a personal project for learning purposes. Feel free to fork and modify.
