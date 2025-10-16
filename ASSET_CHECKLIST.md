# Asset Checklist for Farmer's Math Feast

This checklist helps you verify that all required assets are in place for the game to work properly.

## Quick Start

1. Add all your image (.jpg) and audio (.mp3, .wav) files to the `Assets/` directory
2. Make sure filenames match exactly (case-sensitive, including spaces)
3. Open `index.html` in a web browser to play the game

## Required Assets Checklist

### Images (30 files total)

#### Title & Tutorial (2 files)
- [ ] `Assets/Opening & Tutorial.jpg`
- [ ] `Assets/Title Page.jpg`

#### Backgrounds (6 files)
- [ ] `Assets/BG Theme 1.jpg`
- [ ] `Assets/BG Theme 2.jpg`
- [ ] `Assets/BG Theme 3.jpg`
- [ ] `Assets/Green bg.jpg`
- [ ] `Assets/autumn bg.jpg`
- [ ] `Assets/summer bg.jpg`

#### Game Guide (1 file)
- [ ] `Assets/Game guide.jpg`

#### Mini-Game: Constellations (10 files)
- [ ] `Assets/MiniGameOption1.jpg`
- [ ] `Assets/Mini-game 1 Constellation.jpg`
- [ ] `Assets/Orion.jpg`
- [ ] `Assets/Leo.jpg`
- [ ] `Assets/Big Dipper.jpg`
- [ ] `Assets/Guess It.jpg`
- [ ] `Assets/Guess Leo.jpg`
- [ ] `Assets/Guess Orion.jpg`
- [ ] `Assets/Guess Dipper.jpg`
- [ ] `Assets/ConstellationsFin.jpg`

#### Scarecrow Building Game (10 files)
- [ ] `Assets/Birds and Bunnies.jpg`
- [ ] `Assets/Building the Scarecrow Intro page.jpg`
- [ ] `Assets/Building the Scarecrow Start.jpg`
- [ ] `Assets/Building the Scarecrow Q1.jpg`
- [ ] `Assets/Building the Scarecrow Q2.jpg`
- [ ] `Assets/Building the Scarecrow Q3.jpg`
- [ ] `Assets/Building the Scarecrow Q4.jpg`
- [ ] `Assets/Building the Scarecrow Q5.jpg`
- [ ] `Assets/Scarecrow Complete.jpg`

#### Ending (1 file)
- [ ] `Assets/Ending Page Feast.jpg`

### Audio (4 files total)

#### Music (1 file)
- [ ] `Assets/feast-bgm.mp3`

#### Sound Effects (3 files)
- [ ] `Assets/answer correct.mp3`
- [ ] `Assets/level pass.wav`
- [ ] `Assets/level fail.mp3`

## Verification

Run this command in the repository root to check for missing assets:

```bash
# On Linux/Mac:
for file in "Opening & Tutorial.jpg" "Title Page.jpg" "BG Theme 1.jpg" "BG Theme 2.jpg" "BG Theme 3.jpg" "Green bg.jpg" "autumn bg.jpg" "summer bg.jpg" "Game guide.jpg" "MiniGameOption1.jpg" "Mini-game 1 Constellation.jpg" "Orion.jpg" "Leo.jpg" "Big Dipper.jpg" "Guess It.jpg" "Guess Leo.jpg" "Guess Orion.jpg" "Guess Dipper.jpg" "ConstellationsFin.jpg" "Birds and Bunnies.jpg" "Building the Scarecrow Intro page.jpg" "Building the Scarecrow Start.jpg" "Building the Scarecrow Q1.jpg" "Building the Scarecrow Q2.jpg" "Building the Scarecrow Q3.jpg" "Building the Scarecrow Q4.jpg" "Building the Scarecrow Q5.jpg" "Scarecrow Complete.jpg" "Ending Page Feast.jpg" "feast-bgm.mp3" "answer correct.mp3" "level pass.wav" "level fail.mp3"; do
  if [ -f "Assets/$file" ]; then
    echo "✓ $file"
  else
    echo "✗ MISSING: $file"
  fi
done
```

## Troubleshooting

- **Images not loading**: Check that filenames match exactly (including capitalization and spaces)
- **Audio not playing**: Verify audio files are in the correct format (.mp3 or .wav)
- **Game shows errors**: Open browser developer console (F12) to see specific missing files
