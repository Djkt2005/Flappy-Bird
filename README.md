# Flappy Bird Game

## Overview
This is a **Flappy Bird Game** built using HTML, CSS, and JavaScript. The initial code was inspired by a tutorial from [Code with Faraz](https://www.codewithfaraz.com/content/194/step-by-step-guide-develop-flappy-bird-game-using-html-css-and-javascript-source-code). The game has been enhanced with additional features, including sound effects and improved sprite handling, to make the gameplay more immersive and enjoyable.

---

## Features
- **Core Gameplay**: Players control a bird that must navigate through pipes by "flapping" to stay airborne.
- **Sound Effects**: 
  - Background music plays during the game.
  - A "flap" sound effect is triggered when the bird flaps its wings.
  - A "dying" sound effect plays when the bird collides with an obstacle.
- **Dynamic Sprites**: Enhanced bird and pipe animations add a polished look to the game.
- **Game States**:
  - Pre-start screen with instructions.
  - Running gameplay with scoring based on the number of pipes passed.
  - Game Over screen showing the final score.
- **Responsive Design**: The game scales well across different devices.

---

## How to Play
1. **Start the Game**:
   - Click, tap, or press a key to begin.
2. **Control the Bird**:
   - Click, tap, or press to make the bird flap and gain height.
   - Avoid the pipes and the ground.
3. **Game Over**:
   - The game ends when the bird collides with a pipe or the ground.
   - Restart the game to try again and beat your previous score.

---

## Enhancements Made
- **Added Sound Effects**:
  - Integrated background music that plays continuously during the game and stops on Game Over.
  - A flapping sound triggers whenever the player makes the bird jump.
  - A dying sound effect plays upon collision, creating a dramatic Game Over experience.
- **Improved Sprites**:
  - Updated bird and pipe visuals for a more polished and engaging design.
- **Streamlined Game Flow**:
  - Reset game states after Game Over to ensure a seamless restart.

---

## Technologies Used
- **HTML**: Structures the canvas and game elements.
- **CSS**: Styles the canvas and background for a visually appealing experience.
- **JavaScript**: Implements game logic, animations, sound integration, and user interactions.

---

## File Structure
- **index.html**: The main structure for the game, including canvas and script references.
- **styles.css**: Styles for the game canvas and overall layout.
- **script.js**: Core game logic, including game state management, sprite animation, and sound integration.
- **Assets**: Includes sprite images for the bird, pipes, and background, as well as audio files for sound effects and background music.

---

## Setup and Run
1. Download the project files.
2. Ensure all images and sound files are placed in the correct paths as referenced in the code.
3. Open `index.html` in a browser to start playing the game.

---

## Credits
- Initial tutorial and base code: [Code with Faraz](https://www.codewithfaraz.com/content/194/step-by-step-guide-develop-flappy-bird-game-using-html-css-and-javascript-source-code)
- Enhancements by: Krishant Tanti

---

## Future Improvements
- Add a leaderboard to track high scores.
- Introduce difficulty levels (e.g., faster pipe movements or narrower gaps).
- Improve mobile responsiveness for better gameplay on touch devices.

---

Enjoy your flight through the world of **Flappy Bird**! 🐦✨
