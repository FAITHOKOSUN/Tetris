# Tetris
This project is a demonstration of  JavaScript skills by buiding a tetris game (No Library, except Math).

# Welcome to My Tetris
***

## Task

Playfield is 10×40, where rows above 20 are hidden or obstructed by the field frame to trick the player into thinking it's 10×20. In 2002 Guideline, it could be at least 22 height.
If hardware permits it, a few pixels of row 21 will be visible.
Tetrimino colors are as follows.
Cyan I
Yellow O
Purple T
Green S
Red Z
Blue J
Orange L
In versions that use monochrome screens, or when hardware limitations disallow all colors to be used, the Tetriminos should have distinct hues and patterns to differentiate themselves.
Tetromino start locations
The I and O spawn in the middle columns
The rest spawn in the left-middle columns
The tetriminoes spawn horizontally with J, L and T spawning flat-side first.
Spawn above playfield, row 21 for I, and 21/22 for all other tetriminoes.
Immediately drop one space if no existing Block is in its path
Initial rotation and movement
Super Rotation System/Standard Rotation System (SRS) specifies tetrimino rotation.
Standard mappings for console and handheld gamepads:
Up, Down, Left, Right on D-pad perform locking hard drop, non-locking soft drop (except first frame locking in some games), left shift, and right shift respectively.
A (or its equivalent thereof) rotates 90 degrees counterclockwise, and B (or its equivalent thereof) rotates 90 degrees clockwise.
Shoulder buttons and X (or its equivalent thereof) use hold.
Standard mappings for computer keyboards:
Up arrow and X are to rotate 90° clockwise.
Space to hard drop.
Shift and C are to hold.
Ctrl and Z are to rotate 90° counterclockwise.
Esc and F1 are to pause.
Left, right, and down arrows are the same as on the console.
Number pad controls:
0 is to hold.
8, 4, 6, and 2 are hard drop, left shift, right shift, and soft drop respectively.
1, 5, and 9 are to rotate 90° clockwise.
3 and 7 are to rotate 90° counterclockwise.
Standard mappings for cellphones:
Arrow keys are the same as on the console.
If the cellphone does not have an OK button on the directional pad, the up arrow is to rotate clockwise.
OK to rotate clockwise.
2, 4, 6, and 8 are the same as up, down, left, and right respectively. (2 will always hard drop.)
0 is to hold.
3, 5, 7, and # rotate clockwise.
1, 9, and * rotate counterclockwise.
The left soft key is to pause. - If the cellphone does not have softkeys, the menu button (if separate from the OK button) is to pause.
Standard mappings for remotes:
Number pad is the same as on a cellphone.
Arrow keys are the same as on the console.
OK is to rotate.
Channel + and Menu are to pause.
If the remote does not have certain buttons, one in the same area as the one omitted is used.
So-called 7-bag Random Generator (also called "random bag" or "7 system")
"Hold piece": The player can press a button to send the falling tetrimino to the hold box, and any tetrimino that had been in the hold box moves to the top of the screen and begins falling. Hold cannot be used again until after the piece locks down. Games on platforms with fewer than eight usable buttons (such as the version on iPod) may skip this feature. The combination of hold piece and Random Generator would appear to allow the player to play forever. It must be enabled by default.
Must have sound effects on by default, on rotation, movement, landing on surface, touching a wall, locking, line clear and game over.
Game must have ghost piece function enabled by default.
Terms used in the "help" section:
"Tetriminos" (the capital T is required), as opposed to "tetrominoes", "tetrads" or "pieces".
Letter names, as opposed to "square", "stick", etc.
Designated soft drop speed. Details vary between guideline versions.
Player may only level up by clearing lines or performing T-Spins. Required lines depends on the game.
May use fixed-goal or variable-goal.
Fixed goal is 10 lines
Variable goal is 5 times the level number.
The line values for variable-goal levels are as follows:
Single = 1 line
Double = 3 lines
Triple = 5 lines
Tetris = 8 lines
The game must use a variant of Roger Dean's Tetris logo, although this was true from around 2000 - before the guidelines emerged.
The logo may not have its t-tetrimino split into 4 minoes.
The logo may not be sheared or skewed.
The logo must be 2D.
Game must include a song called Korobeiniki. This must be the default song.
Uses half second lock delay.
The player tops out when a piece is spawned overlapping at least one block (block out), or a piece locks completely above the visible portion of the playfield (lock out).
Must have 1 to 6 next pieces.
6 is the recommended number of next pieces.
Recognition and rewarding of T-spin moves. Conditions vary between guideline versions.
2005 / 2009: 3-corner T
2006: 3-corner T no kick
Multiplayer and Arcade variations must have 15 moves/rotations before lock.
Mini T-spin is when one of the minoes next to pointing side is empty, or holes were made without using the triple kick.
Rewarding of Back to Back chains. (Tetris / T-spin)Recognition method depends on the game.
Marathon mode must have 15 levels.
40 line mode (called sprint or 40 lines)
2 or 3 minute timed mode (called ultra)
Speed curve must be the same as Tetris Worlds.
Game must use a scoring system described here.
Game must count down from 3 after you press start, and after you resume a paused game.
## Description
The game should stop if a Tetrimino fills the highest row of the game board
* The player should be able to rotate each Tetrimino about its own axis
* If a line is completed it should be removed and the pieces above should take its place
* Render a grid-based game in the browser
* Include separate HTML / CSS / JavaScript files
* Use Javascript for DOM manipulation
* Deploy your game online, using Github Pages, where the rest of the world can access it
* Use semantic markup for HTML and CSS (adhere to best practices)


## Installation
To install the Node.js modules http and fs, you can use the following steps:

Make sure you have Node.js installed on your machine. You can download and install Node.js from the official website: https://nodejs.org

Tetris is a tile-matching puzzle game from the 80’s. Try to get your personal high score by moving each of the 5 randomly selected Tetromino shapes sideways and/or rotating by quarter-turns, so that they form a solid horizontal line without gaps. When such a line is formed, it disappears and any blocks above it fall down to fill the space. For each line you will receive 10 points.
### The Core Team
Faith Okosun


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
