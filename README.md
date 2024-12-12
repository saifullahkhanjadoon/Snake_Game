# Snake Game in C

A simple yet fun **Snake Game** implemented in **C programming**. The player controls a snake that moves around the screen, eating fruit to grow longer. The game ends if the snake collides with itself.

## Features:
- **Player Controls**: Use **W**, **A**, **S**, **D** to control the snake’s movement (Up, Left, Down, Right).
- **Game Mechanics**:
  - Snake wraps around the screen if it reaches the boundaries.
  - The snake grows in length after eating fruit.
  - Collision detection with the snake’s body causes the game to end.
  - Score increases by 10 points for each fruit eaten.
- **User Input**: The player can press **X** to quit the game at any time.

## How to Play:
1. Start the game by running the compiled program.
2. Control the snake with the **W**, **A**, **S**, **D** keys.
3. Try to eat the fruit (represented by `*`) to grow the snake.
4. Avoid colliding with the snake’s own body.
5. The game ends if the snake hits its own body or you quit the game by pressing **X**.

## Technologies Used:
- **C Programming Language**
- **conio.h** for console input/output (e.g., `getch()` for reading user input).
- **windows.h** for clearing the screen (`system("cls")`) and managing sleep intervals.

## Setup & Installation:
1. Clone this repository or download the source code.
2. Compile the code with any C compiler:
   - Example: `gcc snake_game.c -o snake_game`
3. Run the compiled executable:
   - On Windows: `snake_game.exe`
   - On Linux/Mac: Ensure you have a compatible library for console handling or modify the code accordingly.

## Contributions:
Feel free to fork the repository, make improvements, and submit pull requests. Contributions are welcome!

---

Enjoy playing the Snake Game! 🐍
