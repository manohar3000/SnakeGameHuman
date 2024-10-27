# Snake Game in Python

This is a simple implementation of the classic Snake game using Python and Pygame. The objective of the game is to control a snake, eat fruit, and grow in length while avoiding collisions with the walls and itself.

## Features

- Classic gameplay with scoring system
- Random fruit generation
- Game-over detection
- High score tracking

## Requirements

To run the game, you need to have Python and Pygame installed on your machine. The following instructions will guide you through the installation and execution process.

## Installation

### 1. Clone the Repository

Open your terminal or command prompt and run the following command to clone the repository:

```bash
git clone https://github.com/your_username/snake-game](https://github.com/manohar3000/SnakeGameHuman.git

```
### 2. Navigate to the Project Directory

Change your directory to the cloned repository:

```bash
cd snake-game
```
### 3. Install Dependencies
It's recommended to create a virtual environment to manage the dependencies. You can use venv as follows:

```bash
python -m venv venv
```
#### Activate the Virtual Environment:

- **On Windows:**
  
  ```bash
  venv\Scripts\activate
  ```
- **On macOS/Linux:**
  
  ```bash
  source venv/bin/activate
  ```
Now install the required packages:
 ```bash
pip install -r requirements.txt
```
## Running the Game
Once all dependencies are installed, you can run the game using the following command:
 ```bash
python game.py
```
## Controls

- **Arrow Keys:** Move the snake (Up, Down, Left, Right).

## Game Logic

- The snake moves in the direction it is facing.
- Eating fruit increases the length of the snake and your score.
- The game ends if the snake collides with the walls or itself.

## Author

Manohar Gehlot

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
