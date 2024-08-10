# Snake Game

This is a classic implementation of the Snake game, inspired by the version found on old Nokia phones. The game is built using HTML, CSS, and JavaScript.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [How to Play](#how-to-play)
- [Code Structure](#code-structure)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Features

- Simple and intuitive gameplay.
- Classic grid-based movement.
- Growing snake as it consumes food.
- Basic collision detection.
- Score tracking.

## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

You will need a web browser that supports HTML5, CSS3, and JavaScript.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/fake-snake.git
   cd fake-snake

   ```

2. Open the game:
   Simply open the index.html file in your web browser to start the game.

## How to Play

### Starting the Game:

- Press the **Spacebar** to start the game.
- The snake will start moving automatically.

### Controlling the Snake:

- Use the arrow keys on your keyboard to control the direction of the snake.
  - **ArrowUp** → Move up.
  - **ArrowDown** → Move down.
  - **ArrowLeft** → Move left.
  - **ArrowRight** → Move right.

### Objective:

- Guide the snake to eat the food that appears on the game board.
- Each time the snake eats food, it grows longer.
- The game ends if the snake runs into the walls or into itself.

### Scoring:

- Your score increases by 1 point for each piece of food eaten.
- The game will display your current score.

## Code Structure

- **`index.html`**: The main HTML file that contains the game structure and links to CSS and JavaScript files.
- **`css folder`**: Contains all the styling rules for the game, including the layout of the game board and snake appearance.
- **`js folder`**: Implements the game logic, including snake movement, food generation, and collision detection.

## Customization

### Change Grid Size

To change the size of the game grid, modify the `gridSize` variable in the `main.js` file. Note that the size of each grid cell is controlled via CSS in the `gamBoard.css` file.

### Adjust Game Speed

To adjust the speed of the snake, modify the `gameSpeedDelay` variable in the `main.js` file.

### Change Snake and Food Appearance

The appearance of the snake and food can be customized in the `components.css` file. Modify the `.snake` and `.food` CSS classes to change their styles.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. Contributions, whether it be bug fixes, feature enhancements, or documentation improvements, are welcome.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

_Feel free to replace "https://github.com/your-username/fake-snake.git" with the actual URL of your GitHub repository and customize any other sections according to your project specifics._
