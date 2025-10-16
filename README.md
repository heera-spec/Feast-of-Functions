# Farmer's Math Feast 🍎🥚🥕

An interactive educational game that helps children learn math through fun farming activities!

## Overview

Farmer's Math Feast is a web-based educational game where players help a farmer by solving math problems. The game includes:
- **3 Main Levels**: Addition, Multiplication, and Mixed Operations
- **Mini-Games**: Constellation guessing game and scarecrow building activity
- **Progressive Difficulty**: Questions adapt based on player performance
- **Engaging Visuals**: Colorful farm-themed graphics and animations
- **Audio Feedback**: Sound effects and background music enhance the experience

## Getting Started

### Prerequisites

You need to provide your own game assets (images and audio files) to run the game. The repository structure is ready, but asset files are not included in version control.

### Setup Instructions

1. **Clone or download this repository**

2. **Add your asset files**
   - Place all required image and audio files in the `Assets/` directory
   - See [ASSET_CHECKLIST.md](ASSET_CHECKLIST.md) for the complete list of 33 required files
   - Filenames must match exactly (case-sensitive, including spaces)

3. **Open the game**
   - Simply open `index.html` in a web browser
   - No build process or server required!

### Required Assets

The game requires 33 asset files:
- **29 image files** (.jpg format): Tutorial screens, backgrounds, game screens, constellation images, scarecrow building sequences, and ending screens
- **4 audio files**: Background music (feast-bgm.mp3) and sound effects (answer correct.mp3, level pass.wav, level fail.mp3)

See [Assets/README.md](Assets/README.md) for detailed descriptions of each file.

Use [ASSET_CHECKLIST.md](ASSET_CHECKLIST.md) to verify you have all required files.

## Game Features

### Level 1: Gathering Apples 🍎
- Learn addition (1-10 range)
- Summer farm theme
- Need 3 correct answers to pass

### Level 2: Collecting Eggs 🥚
- Learn multiplication (2-5 range)
- Green farm theme
- Need 3 correct answers to pass

### Level 3: Harvesting Carrots 🥕
- Mixed multiplication and division (2-5 range)
- Autumn farm theme
- Need 3 correct answers to pass

### Mini-Games

**Constellation Game**: Learn about constellations (Orion, Leo, Big Dipper) through an interactive guessing game.

**Scarecrow Building**: If a player struggles with questions, they get encouragement through a fun scarecrow building activity with practice problems.

## File Structure

```
Feast-of-Functions/
├── index.html              # Main game file
├── Assets/                 # Game assets directory
│   └── README.md          # Detailed asset documentation
├── ASSET_CHECKLIST.md     # Interactive checklist to verify assets
├── .gitignore             # Excludes binary files from version control
└── README.md              # This file
```

## Development

This is a standalone HTML/CSS/JavaScript game with no external dependencies. All game logic is contained in `index.html`.

### Technologies Used
- Pure HTML5
- CSS3 for styling
- Vanilla JavaScript for game logic
- HTML5 Audio API for sound

### Customization

You can customize the game by:
- Adjusting difficulty levels in the `LEVELS` array (search for "Level definitions" in index.html)
- Modifying number ranges and operations
- Changing the number of required correct answers
- Creating your own themed asset files

## Browser Compatibility

The game works in all modern browsers that support:
- HTML5 Audio
- CSS3 Flexbox
- ES6 JavaScript

Tested in Chrome, Firefox, Safari, and Edge.

## License

This is an educational project. Please ensure you have appropriate rights to any asset files you use.

## Contributing

This project is part of an educational repository. If you'd like to contribute improvements:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Support

If assets are not loading:
1. Check browser console (F12) for specific error messages
2. Verify all 33 files are in the Assets directory
3. Ensure filenames match exactly (including capitalization and spaces)
4. Run the verification script in ASSET_CHECKLIST.md

## Acknowledgments

Created as an educational tool to make math learning fun and engaging for children through interactive gameplay and colorful farm themes.
