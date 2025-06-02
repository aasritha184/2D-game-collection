Project 1: Ursina Breakout

Description

Ursina Breakout is a classic brick-breaking arcade game built with the Ursina Game Engine. Players control a paddle to keep a ball in play and break all the bricks. Power-ups grant extra lives, and the game includes both win and lose conditions.

Features

Classic paddle-and-ball brick-breaking gameplay
Responsive paddle controls (Arrow keys)
Lives system (starts with 3 lives)
Power-up drops (gain extra lives)
Game states: Menu, Playing, Game Over
Score tracking and display

Requirements

Python 3.7+
Ursina

Install dependencies using:

pip install ursina

How to Run

1. Save the script as breakout.py.
2. Run it:

python breakout.py

Controls

Key Action
/ Move paddle left/right
Any Key Start game from menu
R Restart after win/loss
ESC Exit the game

Potential Improvements

Add sound effects and background music
Introduce more power-up types
Add levels with varied brick patterns
Add animations or particle effects







Project 2: Photon Dodger v2 (Pygame)

Description

Photon Dodger v2 is a fast-paced survival game made with Pygame. Players must dodge falling photons and collect green power-ups to clear the screen. Survive as long as possible to earn a high score. Features a difficulty selection menu, real-time score tracking, level progression, and a clean pause/game-over system.

Features

Three difficulty levels: Easy, Medium, Hard
Increasing difficulty as levels progress
Random power-ups that clear all photons
Clean UI: Score, Level, Difficulty Display
Pause and resume functionality
Game Over screen with final score and level

Requirements

Python 3.7+
Pygame

Install dependencies using:

pip install pygame

How to Run

1. Save the script as photon_dodger.py.
2. Run it:

python photon_dodger.py

Controls

Key Action
/ Move player ship left/right
ENTER Start game from menu
P Pause/Unpause the game
M Return to menu (from pause screen)
R Restart (from Game Over)
Q / ESC Quit the game
/ Navigate difficulty options in menu

How Scoring Works

Score increases based on how long you survive.
Level up every few seconds depending on difficulty.
Each level increases photon speed and spawn rate.

Potential Improvements

Add different types of power-ups
Leaderboard for high scores
Sound and visual effects
Additional enemy/projectile types
