# XsOs: Noomi's Tic Tac Toe

Noughts and crosses drawn on a recreation of an old pocket-handheld LCD screen: a dot-matrix board, seven-segment score digits and square-wave beeps.

**Play:** https://npsquared.github.io/XsOs/

Everything is in one self-contained file, `index.html`. It has no dependencies or build step, so you can also just open it in a browser.

## Modes

- **1 vs CPU** at three levels. Easy makes plenty of mistakes, Medium blocks your wins but can be tricked with a fork, and Hard plays perfectly, so the best you can get is a draw.
- **2 players** taking turns on the same device.

You are always X against the computer. Who moves first switches every round. The tally (wins, ties, losses) is kept separately for each mode and level, and saved in your browser along with your settings.

## Controls

| Keyboard | Touch | Action |
| --- | --- | --- |
| Arrows or WASD | | Move the cursor |
| Enter or Space | Tap a square | Place your mark |
| 1–9 (number-pad layout, 7 is top left) | | Place on that square |
| N | Tap NEW / NEXT | New round |
| Esc | Tap MENU | Menu |
| M | Tap ♪ | Sound on/off |

On phones held upright the screen uses a tall layout so the board fills the width. Wide screens put the board on the left and the scores and buttons on the right.
