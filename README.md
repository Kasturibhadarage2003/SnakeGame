# Snake Game in Java

## Overview

This project is a simple implementation of the classic Snake Game using Java and the Swing library for GUI components. The game involves controlling a snake to eat apples that appear randomly on the screen. Each time the snake eats an apple, it grows longer. The game ends if the snake collides with itself or the edges of the game window.

## Features

- Basic Snake Game mechanics
- Simple and intuitive controls using arrow keys
- Real-time scoring
- Game over detection
- Clean and minimalistic design

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed
- An Integrated Development Environment (IDE) such as IntelliJ IDEA or Visual Studio Code

### Installation

1. **Clone the Repository:**
    ```sh
    git clone https://github.com/your-username/snake-game-java.git
    cd snake-game-java
    ```

2. **Open the Project in Your IDE:**
    - Open IntelliJ IDEA or Visual Studio Code.
    - Open the folder containing the cloned repository.

3. **Compile the Project:**
    - Compile all Java files:
      ```sh
      javac SnakeGame.java GameFrame.java GamePanel.java
      ```

4. **Run the Game:**
    - Run the main class:
      ```sh
      java SnakeGame
      ```

## Project Structure

- `SnakeGame.java`: The main class that initializes the game.
- `GameFrame.java`: Sets up the main window for the game.
- `GamePanel.java`: Contains the game logic, including rendering, input handling, and game state updates.

## Controls

- **Arrow Keys:**
    - `UP`: Move the snake up
    - `DOWN`: Move the snake down
    - `LEFT`: Move the snake left
    - `RIGHT`: Move the snake right

## How to Play

1. **Start the Game:**
    - When you run the game, a window will appear with the snake in the middle of the screen.

2. **Control the Snake:**
    - Use the arrow keys to control the direction of the snake.

3. **Eat the Apple:**
    - Guide the snake to eat the apples that appear randomly on the screen. Each time the snake eats an apple, it grows longer.

4. **Avoid Collisions:**
    - The game ends if the snake collides with the edges of the window or with itself.

5. **Scoring:**
    - The score increases by one each time an apple is eaten. The score is displayed at the top of the game window.

## Screenshot

![Snake Game Screenshot](path_to_screenshot_image)

## Future Enhancements

- Add multiple difficulty levels
- Implement different types of power-ups
- Add sound effects
- Improve graphics and animations

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the classic Snake Game
- Java Swing documentation

