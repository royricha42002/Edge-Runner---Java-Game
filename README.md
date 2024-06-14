
# EDGE RUNNER - Game Development in Java

This project is a simple game developed in Java using the Swing library. The game involves a player moving right and left on the screen while avoiding enemy sprites. The game ends when the player reaches the edge of the screen or collides with an enemy.




## DEMO

https://www.kapwing.com/videos/666bce886b99258dde502ff8

## COMPONENTS

- Game Board
The game board is the main component of the game. It extends the JPanel class and handles the game logic, including rendering the background image, player, and enemies.

- Player
The player is a sprite that can be moved left and right using the arrow keys. It extends the Sprites class and handles its own movement.

- Enemies
The enemies are sprites that move down the screen. There are two types of enemies: Enemy1 and Enemy2. They also extend the Sprites class and handle their own movement.

- Game Loop
The game loop is responsible for updating and rendering the game state at regular intervals. It uses a Timer to schedule the updates.

- Game Over
The game over logic checks for collisions between the player and enemies, and displays a game over message when a collision occurs.
## HOW TO RUN

- Compile the project using javac and jar commands.
- Run the game using java command:
```bash
java -jar game.jar
```
- Use the arrow keys to move the player left and right.

## LICENSE

This project is licensed under the MIT License. See the LICENSE file for details.

