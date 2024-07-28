**Snake-Game**

A classic Snake game implemented using HTML, CSS, and JavaScript. Move the snake with the arrow keys and try to eat the fruit to increase your score. Restart the game anytime by clicking the "RESTART" button.

**Table of Contents**

•	Features

•	Installation

•	Usage


•	Game Mechanics

**Features**

•	Classic Snake gameplay

•	Responsive design for various screen sizes

•	Restart game functionality

•	Incremental speed based on score

•	Random fruit placement

**Installation**

**1.	Clone the repository or download the code files:**

git clone https://github.com/Shivaram-9/Snake Game. git 

**2.	Open index.html in your browser:** Simply double-click the index.html file or open it via a local server.

**Usage**

1.	Start the game by opening index.html in a web browser.
  
2.	Control the snake using the arrow keys on your keyboard:
   
o	Right Arrow: Move right

o	Left Arrow: Move left

o	Down Arrow: Move down

o	Up Arrow: Move up

3.	Increase your score by eating the fruit that appears randomly on the grid.
   
4.	Restart the game by clicking the "RESTART" button.
   
**Game Mechanics**

•	The game grid consists of 225 tiles.

•	The snake starts with a length of 3 and grows as it eats the fruit.

•	The snake moves in the direction set by the arrow keys and wraps around the grid edges.

•	If the snake runs into itself, the game ends, and you will see "GAME OVER" along with your score.

•	The game speed increases incrementally with the score.

**Code Overview**

**•	HTML (index.html):**

o	Contains the basic structure of the game, including a container for the game grid, score display, and control button.

**•	CSS (style.css):**

o	Styles the game grid, tiles, and overall appearance. Utilizes the Poppins and Potta One fonts from Google Fonts.

**•	JavaScript (script.js):**

o	Handles the game logic, including grid creation, snake movement, fruit generation, and game restart functionality.
