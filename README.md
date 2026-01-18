# Escape Road Game

## Description

A simple 2D endless runner game developed using HTML5 Canvas and JavaScript. The player controls a character that jumps to avoid obstacles while collecting power-ups to achieve the highest possible score.

## Features

- **Endless Gameplay:** The game's difficulty gradually increases as the speed ramps up.
- **Scoring System:** Points are awarded based on survival time, with the High Score saved in the browser's local storage.
- **Power-ups:** Various items that grant the player temporary abilities.
- **Simple Controls:** Easy one-button control.
- **Simple Graphics:** 2D graphics with a parallax background effect.

## How to Play

1.  Open the `index.html` file in your web browser.
2.  The game will start automatically.
3.  Press the **Spacebar** to jump and avoid the red obstacles.
4.  Try to collect the colored items (power-ups) to gain advantages.
5.  The game ends upon collision with an obstacle.
6.  To restart, press the **Spacebar** again.

## Game Mechanics

### Player
- A blue square character that can jump to avoid obstacles.

### Obstacles
- Red squares that periodically appear and move towards the player. Colliding with them ends the game.

### Power-ups
Power-ups appear randomly and can help you achieve a better score:

| Color | Ability | Effect |
|:---|:---|:---|
| **Gold** | Score Multiplier | Doubles the points you earn for 5 seconds. |
| **Deep Sky Blue** | Shield | Protects you from a single obstacle collision. |
| **Lime Green** | High Jump | Increases your jump height for 5 seconds. |
| **Blue Violet** | Slow Time | Slows down the entire game speed for 5 seconds. |

## Technologies Used

- HTML5 (Canvas)
- CSS3
- JavaScript

## How to Run

To run the game, simply open the `index.html` file in any modern web browser.
