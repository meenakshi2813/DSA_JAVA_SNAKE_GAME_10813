# 🐍 Console-Based Snake Game in Java

## About the Project
This is a console-based Snake Game developed using Java. The game runs on a 10×10 grid where the player controls the snake using W, A, S, and D keys. The objective is to eat food, increase the score, and avoid hitting the walls or the snake's own body.

This project demonstrates the practical implementation of Java data structures, file handling, sorting algorithms, and basic game logic.

## Features
- 10×10 game grid
- Snake movement using W, A, S, D keys
- Food generation at available positions
- 10 points for each food eaten
- Wall and self-collision detection
- Score saving in a text file
- Top 5 leaderboard
- Test cases for different game scenarios
- Invalid input handling

## Technologies Used
- **Language:** Java
- **Data Structures:** ArrayDeque, HashSet, 2D Array
- **Algorithms:** Insertion-based sorting
- **File Handling:** BufferedReader, BufferedWriter, FileReader, FileWriter
- **Input Handling:** Scanner

## How the Game Works
1. The snake starts at position (5,5) on the grid.
2. The player controls the snake using W (Up), A (Left), S (Down), and D (Right).
3. The snake moves in the selected direction.
4. When the snake eats food, the score increases by 10 and its length grows.
5. The game ends when the snake hits a wall or its own body.
6. Scores are saved in `scores.txt` and the Top 5 leaderboard is displayed.

## Data Structures Used

| Data Structure | Purpose |
|---|---|
| ArrayDeque | Manages the snake's head and tail |
| HashSet | Checks body collision efficiently |
| 2D Array | Represents and displays the game board |

## Algorithms Used
- **Collision Detection:** Checks wall boundaries and snake body collisions.
- **Food Placement:** Selects an available cell without random retry loops.
- **Insertion-based Sorting:** Maintains the Top 5 scores in descending order.

## How to Run

### Requirements
- Java JDK 11 or later
- Terminal or Command Prompt

### Steps

1. Clone the repository:

   ```bash
   git clone YOUR_REPOSITORY_LINK
   ```

2. Navigate to the project directory:

   ```bash
   cd YOUR_REPOSITORY_FOLDER
   ```

3. Compile the Java program:

   ```bash
   javac SnakeGame.java
   ```

4. Run the game:

   ```bash
   java SnakeGame
   ```

## Menu Options
- `1` – Play Game
- `2` – Run Test Cases
- `3` – Show Top 5 Scores
- `4` – Exit

## Future Scope
- Graphical user interface using Java Swing or JavaFX
- Difficulty levels
- Sound effects
- Obstacles and power-ups
- Database integration for player records
- Multiplayer functionality

## Learning Outcomes
- Understanding Java data structures
- Implementing game logic
- Using arrays and collections
- Implementing collision detection
- Working with file handling
- Applying sorting algorithms
- Writing and executing test cases

