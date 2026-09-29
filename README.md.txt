# Highway Rush

Highway Rush is a browser-based endless traffic racing game built with HTML, CSS, and JavaScript.

The player controls a car across three highway lanes and avoids incoming traffic. The game becomes faster as the player survives longer.

## Features

- Endless highway racing gameplay
- Three traffic lanes
- Keyboard and on-screen controls
- Increasing difficulty over time
- Score and best-score tracking
- Pause and resume functionality
- Automatic pause when the browser tab becomes hidden
- Best score saved using browser `localStorage`
- Responsive layout for desktop and mobile screens
- No external libraries or dependencies

## How to Play

1. Open the HTML file in a modern web browser.
2. Select **Start racing**.
3. Move the green car between lanes.
4. Avoid the incoming vehicles.
5. Survive as long as possible to increase your score.

The game ends when the player collides with another vehicle.

## Controls

| Control | Action |
|---|---|
| Left Arrow | Move left |
| Right Arrow | Move right |
| A | Move left |
| D | Move right |
| Space | Pause or resume |
| On-screen left button | Move left |
| On-screen right button | Move right |
| Pause button | Pause or resume |

## Scoring

The score is calculated from the time survived:

```text
Score = elapsed time × 10
