<h1 align="center">
  Flappy Bird
</h1>
<p align="center">
  This repository contains a simple implementation of the classic Flappy Bird game using C++ and the SFML (Simple and Fast Multimedia Library) for graphics.
</p>

## How to Play

**Start the Game** 
1. Run the program, and the game will start in a waiting state.
2. Press the "Enter" key to begin playing.

**Game Controls** 
1. Press the "Space" key to make the flappy bird jump and navigate through the pipes.
2. Avoid colliding with the pipes and the top/bottom of the screen.

**Scoring**
1. Score points by successfully navigating through the pipes.
2. The score is displayed at the top of the window.

**Game Over** 
1. If the bird collides with a pipe or goes out of bounds, the game ends.
2. Press "Enter" to restart the game after a game over.

## Code Structure
- [x] The game is structured using the SFML library for graphics and input handling.
- [x] The main game loop is responsible for handling user input, updating the game state, and rendering graphics.

## How to Build
1. Install SFML: Download and install the SFML library on your system.
2. Build the Code:
   Use a C++ compiler to build the source code. You may use an integrated development environment (IDE) or a command-line compiler.
   ```bash
    g++ -o flappy_bird flappy_bird.cpp -lsfml-graphics -lsfml-window -lsfml-system
   ```
3. Run the Executable:
    Execute the generated executable to start the game.

## Showcase
|Game Start|Play|Game Over|
|--|--|--|
|![image](https://github.com/aniindyta/Flappy-Bird/assets/87638112/8ae80166-e8c6-450c-a9d0-dea0f701cd42)|![image](https://github.com/aniindyta/Flappy-Bird/assets/87638112/924e51e2-57c6-4419-b3d2-72bedd5490e8)|![image](https://github.com/aniindyta/Flappy-Bird/assets/87638112/f4c5b49e-bf6e-4422-b2a5-e655f252081c)|
