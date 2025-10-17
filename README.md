# Farmer's Math Feast

An educational math game designed to help children learn addition, multiplication, and division through fun farm-themed activities.

## Overview

Farmer's Math Feast is an interactive browser-based game with three levels:
1. **Level 1: Gathering Apples** - Addition problems
2. **Level 2: Collecting Eggs** - Multiplication problems
3. **Level 3: Harvesting Carrots** - Mixed multiplication and division problems

The game includes:
- Interactive tutorials and transitions
- A mini-game featuring constellation identification
- Encouraging feedback and help activities (Building the Scarecrow)
- Sound effects and background music
- Progress tracking across levels

## Setup

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, or Edge)
- Game asset files (images and audio)

### Installation

1. Clone this repository
2. Add the required asset files to the `Assets` directory
   - See `Assets/README.md` for a complete list of required files
3. Open `index.html` in your web browser

## Missing Assets

**Important:** This repository currently does not include the game's image and audio assets. The `Assets` directory contains a README listing all required files. You will need to:

1. Obtain or create the following types of assets:
   - Title and tutorial screens
   - Background images for each level
   - Constellation images for the mini-game
   - Encouragement and activity screens
   - Sound effects and background music

2. Place them in the `Assets` directory with the exact filenames specified in `Assets/README.md`

Without these assets, the game will not display properly, though the game logic will still function.

## Game Features

### Main Game
- **Three Progressive Levels**: Each level increases in difficulty
- **Word Problems**: Contextual math problems related to farm activities
- **Progress Tracking**: Players must get 3 out of 5 questions correct to pass each level
- **Encouragement System**: If a player gets 2 wrong answers in a row, they're guided through a practice activity

### Mini-Game
- **Constellation Game**: An optional side activity where players learn to identify constellations (Orion, Leo, and Big Dipper)

### Game Guide
- Accessible from the title screen
- Provides instructions on how to play

## Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- No external dependencies required
- Responsive design that adapts to different screen sizes
- Uses HTML5 audio for sound effects

## File Structure

```
Feast-of-Functions/
├── index.html          # Main game file
├── Assets/             # Asset directory
│   ├── README.md       # List of required assets
│   └── .gitkeep        # Ensures directory is tracked by git
└── README.md           # This file
```

## Browser Compatibility

The game is compatible with modern browsers that support:
- HTML5
- CSS3 (Flexbox)
- ES6 JavaScript
- HTML5 Audio API

## Contributing

When contributing assets or improvements:
1. Ensure all asset filenames match those specified in `Assets/README.md`
2. Test the game in multiple browsers
3. Keep the educational focus appropriate for young learners

## License

Please ensure you have appropriate rights to any assets you add to this project.
