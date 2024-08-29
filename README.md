# Breakout-Ball-Game
In this game be break or popup the Bricks using a Ball.
And for every brick user will get 5 points.


# Run
We can directly play the game by running the breakout ball game executable jar file . Through this you can direectly able to play the game.


# Steps involve:
Design the game window
Design the gameplay (background, bricks, ball, and paddle)
Implement the actions of the keys (to move the paddle sideways).
Implement the action performed by the ball on the bricks and paddle.


# You should be able to achieve these goals at the end of the game:
The player should be able to start the game by pressing the ENTER key.
The player should be able to move the paddle horizontally using left and right arrow keys on the keyboard.
Once the player loses the ball, i.e. when the ball touches the bottom of the window, the game ends.
Breaking each brick should provide the player a certain score. Let’s say each brick contains 5 points, if a player breaks 10 such bricks, he gets a score of 50.
At the end of the game, the terminal will present the player’s final score and give him the option to restart the game again.
In our game, we have one paddle, one ball, and 21 bricks. I have created a ball, paddle, and brick using graphics class in java. To create the game cycle, we will use the Timer class. For the sake of simplicity we are not working with angles, we simply change directions to top, bottom, left, and right. The game consists of three files: Main.java, Gameplay.java, and MapGenerator.java. We will talk about each class in detail. So, let's get started.



