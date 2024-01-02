# Car-Game

Game Structure:

The game consists of three modes: Easy, Medium, and Hard.
The easyClass, mediumClass, and hardClass classes handle the specific gameplay for each mode.
The game window has a defined size with a width of 90 characters and a height of 26 characters.
The game screen (play area) has a width of 70 characters (WIN_WIDTH).
The player's car is represented by a 4x4 matrix of characters, and there are different car designs for each difficulty mode.
Enemies are represented by various characters and move downward on the screen.
Gameplay:

The main menu allows the player to choose between Easy, Medium, Hard modes, or go back.
Each mode has different enemy designs, speeds, and difficulty levels.
The player controls the car using 'A' (left) and 'D' (right) keys.
The objective is to avoid collisions with enemies while navigating the car.
The game keeps track of the player's score, which increases as the player successfully avoids enemies.
If the player's car collides with an enemy, the game ends, and a game-over screen is displayed.
Additional Features:

The game uses the conio.h and windows.h libraries for handling console input/output and creating a visual interface.
The dos.h library is included, indicating that the game uses some functions related to MS-DOS compatibility.
The game has specific designs for the car and enemies in each difficulty mode.
There are instructions provided for each mode, displayed before the game starts.
