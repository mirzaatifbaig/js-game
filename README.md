# Platformer Game

This is a simple platformer game implemented using JavaScript, HTML, and CSS. The game includes player movement, collectible coins, and hazardous lava. The goal is to collect all the coins while avoiding the lava.

## Features

- **Player Movement**: Move left, right, and jump using arrow keys.
- **Hazards**: Avoid the lava which can move horizontally, vertically, or drop from above.
- **Collectibles**: Collect all the coins to win the level.
- **Dynamic Rendering**: The game dynamically renders the level and updates the player's status.

## Getting Started

### Prerequisites

To run this game, you need a modern web browser that supports JavaScript.

### Installation

1. Clone the repository or download the source code.
2. Open the `index.html` file in your web browser.

### Running the Game

1. Open the `index.html` file in your web browser.
2. Use the arrow keys to control the player:
   - **Left Arrow**: Move left.
   - **Right Arrow**: Move right.
   - **Up Arrow**: Jump.

### Code Overview

- `Level`: Represents the game level, including layout and actors.
- `State`: Manages the current state of the game.
- `Vec`: A utility class for vector operations.
- `Player`, `Lava`, `Coin`: Classes representing different actors in the game.
- `DOMDisplay`: Handles rendering of the game in the web browser.
- `drawGrid`, `drawActors`: Functions to render the level grid and actors.

### Level Plan

A sample level plan is defined using ASCII characters:

```plaintext
####################
#.............=....#
#.........o........#
#.............=....#
#.......@..........#
####################
