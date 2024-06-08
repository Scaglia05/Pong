Ping Pong Game in p5.js

This is a simple ping pong game developed using the p5.js library. The game consists of hitting a ball with a racket, controlled by the player, in order to prevent the ball from going over the racket and scoring points by making the ball go over the opponent's racket.

Main Features

Variables and Initial Settings
Ball Variables:
xbolinha, ybolinha: Coordinates of the ball on the screen.
diameter, radius: Dimensions of the ball.
Ball Speed:
xvelocity, yvelocity: Determine the speed of the ball on the x and y axes.
Opponent Racket Variables:
xopponent racket, yopponent racket: Coordinates of the opponent's racket.
racketlengthop, racketheightop: Dimensions of the opponent's racket.
opponent speed, chance of error: Parameters for the opponent's automatic movement and probability of error.
Player Racket Variables:
xracket, yracket: Coordinates of the racket controlled by the player.
racket length, racket height: Dimensions of the player's racket.
Game Score:
mypoints, opponent's points: Store the player's and opponent's points.
Sounds
Loaded Sounds:
racket: Sound played when the ball collides with a racket.
point: Sound played when marking a point.
soundtrack: Background soundtrack during the game.
Main Functions
Setup:

Configures the game environment, sets the screen size and starts the soundtrack.
Main Loop (Draw):

Design and update game elements (ball, rackets, scoreboard).
Detects collisions and updates the position of elements.
Movement:

Allows the player to move his racket up and down.
Collision:

Checks whether the ball collides with the player's and opponent's rackets.
Punctuation:

Updates the scoreboard when a point is scored.
Movement Limitation:

Prevents rackets from leaving the screen.
How to play
Use the arrow keys to move the racket up and down.
Hit the ball with the racket to prevent it from going over the racket.
Score points by getting the ball past your opponent's racket.
Whoever scores the most points wins.
Have fun playing ping pong!

Installation and Execution
Clone or download this repository.
Open the index.html file in a web browser compatible with the p5.js library.
Enjoy the game!
