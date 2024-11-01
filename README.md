# Yatzy Game Design Documentation


## Overview
This project is part of CST3106 - LAB 05, where I developed and documented a single-player Yatzy game using a structured design system approach. Yatzy is a classic dice game where players aim to score points by rolling five dice to form specific combinations.


## Lab Steps


### 1. Game Documentation in Markdown
This section provides an overview of the Yatzy game and its rules. Players roll five dice in an attempt to score points through various combinations. The game concludes when all score categories are filled, and the player with the highest total score is declared the winner.


#### Game Rules
- **Roll Five Dice**: Players roll five dice each turn.
- **Re-rolls**: Players may hold certain dice and re-roll the remaining ones up to two additional times during their turn.
- **Scoring**: Each turn, players must select a category to score points. Available scoring categories include:
 - **Ones, Twos, Threes, etc.**: Score based on the number of matching dice.
 - **Three of a Kind**: Total of all dice if at least three dice are the same.
 - **Four of a Kind**: Total of all dice if at least four dice are the same.
 - **Full House**: Three of one number and two of another, scoring 25 points.
 - **Small Straight**: Four consecutive numbers, scoring 30 points.
 - **Large Straight**: Five consecutive numbers, scoring 40 points.
 - **Yatzy**: Five of a kind, scoring 50 points.
 - **Chance**: Total of all dice.


The game ends when all categories have been filled, and the player's total score is displayed.


### 2. Design System Documentation


#### Color Scheme
- **Primary Color**: `#3498db` (Light Blue)
- **Secondary Color**: `#e74c3c` (Bright Red)
- **Background Color**: `#f1f1f1` (Light Gray)
- **Text Color**: `#2c3e50` (Dark Gray)


These color choices provide a visually appealing contrast that enhances readability and contributes to a pleasant user experience.


#### Fonts
- **Headings**: `'Montserrat', sans-serif`
- **Subheadings**: `'Lato', sans-serif`
- **Body Text**: `'Open Sans', sans-serif`


These font selections focus on clarity and modern aesthetics, ensuring readability and a consistent style throughout the game interface.


### 3. Dice Design


#### Dice Look and Feel
- **Size**: Each die measures 100x100 pixels.
- **Dice Color**: White (`#ffffff`).
- **Pip Color**: Black (`#000000`).
- **Pips (Dots)**: Circular dots evenly spaced on each face of the die.


This straightforward and clean design ensures that the dice are easy to read and distinguish during gameplay.


### 4. Game Mock-ups


#### HTML/CSS Mock-ups
The game will feature a sleek and responsive user interface. The main components include:


- **Dice Area**: Displays the five dice and allows the player to hold and roll them.
- **Scorecard**: Shows the current score and enables the player to select a category to score after each turn.
- **Roll Button**: A button that allows the player to roll or re-roll the dice.


Here is a basic HTML structure for the mock-up:


```html
<!-- Dice Area -->
<div class="dice-area">
 <div class="dice">1</div>
 <div class="dice">2</div>
 <div class="dice">3</div>
 <div class="dice">4</div>
 <div class="dice">5</div>
</div>


<!-- Scorecard -->
<div class="scorecard">
 <div class="score-category">Ones: <span class="score">0</span></div>
 <div class="score-category">Twos: <span class="score">0</span></div>
 <!-- Other categories... -->
</div>

<!-- Roll Button -->
<button class="roll-btn">Roll Dice</button>
