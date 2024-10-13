# Brick Breaker Game Using Java

A classic Brick Breaker game built using Java and Swing. The game starts with a simple title screen and a "Start" button. The player controls a paddle to bounce a ball and break bricks on the screen. The goal is to break all the bricks without letting the ball fall below the paddle.

## Features
- **Brick Layout**: A 3x7 grid of bricks that the player must break.
- **Paddle Control**: Use the left and right arrow keys to move the paddle.
- **Ball Physics**: The ball bounces off the paddle and the walls, and breaks bricks when it hits them.
- **Score System**: Earn points for each brick broken. The game displays the score in real-time.
- **Game Over & Win Screen**: If the ball falls below the paddle, the game ends with a "Game Over" screen. If all the bricks are broken, the player wins.
- **Restart Functionality**: Press "Enter" to restart the game after winning or losing.

## Getting Started
To play the game, clone this repository and compile the Java code.

### Prerequisites
Make sure you have Java installed. You can check if Java is installed by running:

```bash
java -version
```

If Java is not installed, download and install it from [here](https://www.oracle.com/java/technologies/javase-downloads.html).

### Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/CodeLychee/.git
```

2. Navigate to the project directory:

```bash
cd brickbreakergame
```

3. Compile the game:

```bash
javac BrickBreakerGame.java
```

4. Run the game:

```bash
java BrickBreakerGame
```

## How to Play

- **Start the Game**: Click the "Start" button on the title screen or hover and press "Enter" to begin.
- **Move the Paddle**: Use the arrow keys to move the paddle left or right.
- **Bounce the Ball**: Prevent the ball from falling by bouncing it off the paddle. Hit the bricks to break them.
- **Win**: Break all the bricks to win the game.
- **Game Over**: If the ball falls below the paddle, the game will end. Press "Enter" to restart.

## Known Issues
- **Ball Stuck Issue**: In rare cases, the ball may get stuck between bricks.
- **Improvement**: Adding levels or increasing difficulty as the game progresses.

## Future Enhancements
- Add sound effects for paddle and brick collisions.
- Implement multiple levels with varying brick layouts.
- Add power-ups (e.g., ball speed change, larger paddle).

## Contributing

Contributions are welcome! If you'd like to contribute, feel free to fork this repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
