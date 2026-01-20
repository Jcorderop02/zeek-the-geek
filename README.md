Zeek the Geek HTML5
===================

HTML5 clone of 1995's game *Zeek the Geek*, please use modern browsers like Chrome, Microsoft Edge to play this game.

## Modifications

This is a modified version of the original game with the following changes:

- **Level Selector**: Added a "Go to:" dropdown menu that allows players to jump directly to any level within a puzzle pack, without having to complete previous levels first.

## How to Play

1. Open `index.html` in your browser, or use a local server:
   ```
   python3 -m http.server 8000
   ```
   Then open `http://localhost:8000`

2. Select a Puzzle Pack from the list
3. Use arrow keys or mouse to control Zeek
4. Use the "Go to:" dropdown to jump to any level

## Puzzle Packs

| Puzzle Pack | Levels |
|-------------|--------|
| Zeek 1 | 15 |
| Zeek 2 | 30 |
| Nice 'n Easy | 30 |
| Kid's Stuff | 30 |
| Galore | 60 |
| Challenge | 30 |
| Challenge II | 30 |
| Fun Pack 1 | 5 |
| Valentine 1 | 3 |

**Total: 233 levels**

## Technical Information

**WebAudioAPI** is used to play sound.

**localStorage** is used to store settings and gaming progress for each puzzle pack.

All the gaming engine related code are at `js` folder, then packed and compressed into `game.js` via **rollup**.

## Credits

- Original game by [Frank Deng](https://github.com/frank-deng/zeek-the-geek)
- Licensed under MIT License
