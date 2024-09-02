#Space Game

##Description
This is a basic interactive game built with JavaScript. It features a game element that starts when the user clicks anywhere on the screen or presses the Space key. The game involves tracking and locking elements on the screen, with a scoring system that updates based on user interactions.

##How It Works
**Initialization**:

- The game starts by hiding the "start" element and triggering the game logic when a click or Space key press is detected.

**Game Logic**:

- `Object` Class: Manages the position and size of game elements.
- `Generate` Function: Initializes game elements and starts the game loop.
- `Lock` Function: Adjusts the size and position of the lock element.
- `Key` Function: Moves the key element back and forth, checking for collisions with the lock element.
- `Unlock` Function: Checks if the key element is outside the lock's area to reset or increase the score.

**Usage**
- Click anywhere on the screen or press the Space key to start the game.
- The game will display and update a score based on interactions between game elements.
