Boccette & Matamà - Arcade Battle" is an arcade-style game based on the traditional Italian game of boccette. Developed using HTML5, CSS3, and JavaScript with the p5.js library, this game offers a fun and engaging experience for two players. The game simulates the physics of balls on a billiard table, including collisions, friction, and a central castle. With simple yet appealing graphics and intuitive controls, "Boccette & Matamà" is a modern tribute to a classic tabletop game.

Features

Arcade-style graphics using HTML5 Canvas and p5.js 
Realistic physics for ball collisions and movement
Two-player game mode
Customizable table (dimensions and friction)
Scoring and turn-based system
Visual effects such as predicted ball trajectory

Technologies Used

HTML5
CSS3
JavaScript
p5.js for graphics and animation

Installation

Clone the repository:
Copygit clone https://github.com/yourusername/boccette-matama.git

Open the index.html file in a modern web browser.

How to Play

Configure the table dimensions and friction coefficient (optional).
Click "Start Game".
Click on your colored ball to initiate the shot.
Move the mouse to adjust the direction and power of the shot.
Click again to execute the shot.
The goal is to hit the central castle with the opponent's ball.

Customization
You can modify various game parameters, including:
Table dimensions
Friction coefficient
Number of rounds
Visual appearance (by modifying the CSS)

Code Structure

index.html: HTML structure of the game
<style>: Embedded CSS for game styling
<script>: JavaScript code for game logic

Main Components

Ball: Class for managing balls
Castle: Class for the central castle
setup(): Game initialization
draw(): Main game loop
handleShotEnd(): Handling the end of each shot
checkCollision(): Collision detection and handling
