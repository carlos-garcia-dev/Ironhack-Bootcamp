<div align="center">
    <img 
        alt="Ironhack"
        width="300px"
        src="https://github.com/carlos-garcia-dev/Ironhack-Bootcamp-Images/blob/main/project1-Videogame/Game_logo.png" />
</div>
<div align="center">
  <h1>Videogame - Module 1</h1>
  <strong>Remake of a videogame to learn OOP and Classes</strong>
</div>

</br>

## Introduction

First project we finished at the module 1 in Ironhack its main purpose was to get familiar with the _Object Oriented Programming principles_ - OOP and _Class Programming_ with Vanilla JavaScript ES6+ and Canvas.
It was a remake of a top-down shooter videogame which it is focused on constant action. The MVP - Minimun Viable Product, we did in one week included an dynamic counter for the score and lives, besides an special attack reward.

- The project was made by _Carlos Dávila_ and _Carlos García_.

![project1-Game_00](https://github.com/carlos-garcia-dev/Ironhack-Bootcamp-Images/blob/main/project1-Videogame/Game_00.jpg)

## Project

One of the pain points of the project was to solve the difficulty of how the shots are oriented and follow and specific direction according to the mouse-click. It was crucial for a better experience and more natural collisions.

### Example

<img
    alt="Game_animation"
    width="100%"
    src="https://github.com/carlos-garcia-dev/Ironhack-Bootcamp-Images/blob/main/project1-Videogame/Game_animation.gif" />

## Controls

|    Control     |          Action           |
| :------------: | :-----------------------: |
|   **Enter**    |      Start the game       |
| **Left-Click** |           Shoot           |
|   **Space**    | Special 360 attack **\*** |
|     **W**      |          Move up          |
|     **A**      |         Move left         |
|     **S**      |         Move down         |
|     **D**      |        Move right         |

- Press **Enter** to Play
- Move your mouse to aim and **left-click** to shoot
- **WASD** keys to move in every direction
- Press **Space** bar for a 360° attack
- **\*** Each 25 kills you get one 360 attack

## Archives organization

```bash
├── 📁 js
│   ├── background.js
│   ├── bullets.js
│   ├── enemies.js
│   ├── estructuras.js
│   ├── game.js
│   ├── index.js
│   └── player.js
├── README.md
├── 📁 audio
│   ├── GiorgiaAngiuli-PinkTechno.mp3
│   └── 📁 effects
│       ├── deadPlayer.mp3
│       └── gunshot.mp3
├── 📁 img
│   ├── 📁 backgrounds
│   │   ├── background.png
│   │   ├── gameOver.png
│   │   └── mainMenu.png
│   ├── 📁 enemies
│   │   ├── basicEnemy1.png
│   │   ├── basicEnemy2.png
│   │   ├── shooterEnemy1.png
│   │   └── shooterEnemy2.png
│   ├── 📁 items
│   │   ├── bullet1.png
│   │   └── enemyBullet1.png
│   └── 📁 player
│       ├── health.png
│       ├── player.png
│       └── score.png
└── index.html
```

## Installation

1. Clone or download the repository
2. Execute the archive: `index.html`
