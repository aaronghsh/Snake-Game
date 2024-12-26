# C++ Snake Game 🐍

Welcome to the Snake Game project! This game is a modern take on the classic Snake game, designed using **Object-Oriented Design (OOD)** principles to ensure modularity, efficiency, and maintainability. It includes exciting gameplay mechanics such as multi-food spawning, special food generation, and dynamic player movement.

---

## Technologies Used

- **C++**: Core language for implementing the game logic and mechanics.
- **Ncurses Library**: For rendering the game on the console with smooth and interactive visuals.
- **Object-Oriented Design Principles**: To ensure modular, reusable, and maintainable code through encapsulation, inheritance, and polymorphism.
- **Dynamic Memory Management**: To efficiently handle the game's data structures and objects.

---

## Features

- **Multi-Food Spawning**: Generates up to three food items on the board at random positions.
- **Special Food Mechanic**: Includes a chance for special food to spawn, adding strategic elements to the gameplay.
- **Player Movement & Collision Detection**: Smooth directional controls with robust collision detection to handle food pickups and self-collisions.
- **Dynamic Snake Growth**: The snake grows in size as it consumes food, maintaining its position on the board efficiently.
- **Boundary Wrapping**: Snake reappears on the opposite edge of the board when moving out of bounds.

---

## How to Play

1. **Run the Game**: Compile the project files and execute the game in your terminal.
2. **Controls**: Use the following keys to control the snake:
   - `W` or `w`: Move Up
   - `A` or `a`: Move Left
   - `S` or `s`: Move Down
   - `D` or `d`: Move Right
   - `Esc`: Exit the game
3. **Objective**: Eat food to grow the snake and increase your score. Avoid colliding with yourself!

---

## Project Files

- `GameMechs.cpp` and `GameMechs.h`: Manage core game mechanics and input handling.
- `Player.cpp` and `Player.h`: Handle player movement, snake growth, and collision logic.
- `Food.cpp` and `Food.h`: Define food spawning, including special food mechanics.
- `objPos.cpp` and `objPos.h`: Represent positions on the board and provide utilities for comparisons.
- `objPosArrayList.cpp` and `objPosArrayList.h`: Custom array list implementation to manage snake body and food positions.

---

## Future Improvements

- Add more advanced gameplay features like obstacles and levels.
- Implement a graphical user interface (GUI) for a more immersive experience.
- Include a leaderboard to track high scores.

---

Enjoy playing the Snake Game! 🐍
