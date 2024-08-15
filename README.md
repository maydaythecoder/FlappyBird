# Flappy Bird Game in Java

This project is a simple implementation of the classic Flappy Bird game using Java Swing for the graphical user interface (GUI). The game involves a bird that the player controls by pressing the spacebar to navigate through a series of pipes without crashing.

## Project Structure

```
├──Flappybird
│ ├── src/
│ │  ├── firstProject/
│ │  │   ├── App.java
│ │  │   ├── FlappyBird.java
│ │  │   ├── flappybirdbg.png
│ └──│   ├── flappybird.png
│    └── ├── toppipe.png
│        └── bottompipe.png
└── license.txt
```

### Key Files and Directories

- **App.java:** The main class that initializes the game and sets up the JFrame.
- **FlappyBird.java:** The core class that contains the game logic, including rendering the bird, pipes, and background, as well as handling user input and game state.
- **flappybirdbg.png:** The background image for the game.
- **flappybird.png:** The image of the bird that the player controls.
- **toppipe.png:** The image for the top pipe obstacle.
- **bottompipe.png:** The image for the bottom pipe obstacle.

## How to Run the Game

### Prerequisites

- You need to have Java installed on your system. The game is developed using Java SE (Standard Edition).

### Steps to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/maydaythecoder/FlappyBird.git
   cd FlappyBird
   ```

2. **Compile the Java Files:**
   Navigate to the `src` directory and compile the Java files:
   ```bash
   javac firstProject/App.java firstProject/FlappyBird.java
   ```

3. **Run the Game:**
   Run the `App` class to start the game:
   ```bash
   java firstProject.App
   ```

## Gameplay

- **Objective:** The objective of the game is to navigate the bird through the gaps between the pipes. The bird automatically falls due to gravity, and the player must press the spacebar to make the bird "flap" and gain altitude.

- **Controls:**
  - Press `SPACEBAR` to flap the bird's wings and ascend.
  - The game ends when the bird hits a pipe or the ground.

- **Scoring:** The score increases by 1 for each set of pipes the bird successfully passes.

## Game Assets

- **Background:** The background image (`flappybirdbg.png`) provides the backdrop for the game.
- **Bird:** The bird image (`flappybird.png`) represents the player-controlled character.
- **Pipes:** The top and bottom pipes (`toppipe.png` and `bottompipe.png`) serve as obstacles for the bird.

## Future Enhancements

- Add sound effects for flapping and collisions.
- Implement a start screen and a game-over screen.
- Introduce more challenging levels with varying pipe speeds and distances.

## License

This project is open-source and available under the [MIT License](LICENSE).
