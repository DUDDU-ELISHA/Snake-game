# Snake-game

How the Game Works:
Objective:
The objective of the game is to control a snake on a grid and eat food items to grow in length. The game ends if the snake collides with itself or the boundaries of the game screen.

Setup
The game screen is a square grid with dimensions of 600x600 pixels.
The snake starts in the center of the grid, facing a default direction (typically right).
Food items appear randomly on the grid for the snake to eat.
Gameplay Mechanics
Snake Movement:

The snake moves continuously in the direction it was last directed by the player (using arrow keys).
Arrow keys (UP, DOWN, LEFT, RIGHT) control the direction of the snake's movement.
The snake wraps around the screen edges, meaning if it moves off one edge, it appears on the opposite edge of the screen (like in classic snake games).
Eating Food:

Food items appear randomly on the grid as small circles.
When the snake’s head (the front segment) collides with a food item, it consumes the food.
Upon eating food, the snake grows longer by adding a new segment to its tail.
Growing and Scoring:

Each time the snake eats food, the player's score increases.
The game speed may increase as the snake grows longer or based on game settings.
Game Over Conditions:

The game ends if the snake collides with itself (when its head intersects with any part of its body).
The game also ends if the snake collides with the screen boundaries (if not set to wrap around).
Features
Color Scheme:

The snake's is light yellow in colour.
Food items are represented by dark blue circles.
User Interaction:

Players control the snake's movement using arrow keys.
The game responds in real-time to player input, updating the snake's position and checking for collisions.
Future Improvements
Additional features could include:
Increasing game difficulty over time.
Adding obstacles or hazards on the grid.
Implementing levels with different challenges or objectives.
Installation
Requirements
Before running the game, make sure you have the following installed:

Python 3.x
Pygame Library (pip install pygame)
Installation Steps
Clone the Repository: git clone https://github.com/DUDDU-ELISHA/Snake-game.git

Install Pygame: If Pygame is not installed, install it using pip: pip install pygame

And at last Run the Game
