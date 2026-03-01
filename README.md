# cse423_project_coincollector
its a computer graphics project
Game Features
Game Title: CoinQuest 3D

1. Game Overview
CoinQuest 3D is a simple 3D exploration and collection game where the player navigates a small 3D environment to collect coins.
The game includes cheat modes to demonstrate real-time manipulation of movement, physics, and rendering, making it suitable for a computer graphics project.

2. Core Game Features

2.1 3D Player Movement System
Free movement in a 3D environment.
Player can move forward, backward, left, and right.
Jump functionality for basic navigation.
Smooth movement 

2.2 3D Environment
Small enclosed 3D world (ground + boundaries).
Static objects such as walls and obstacles.
Coins placed at different positions in 3D space.
Simple textures

2.3 Coin Collection System
Coins are represented as 3D objects.
Collision detection between player and coins.
Coin disappears upon collection.
Score increments when a coin is collected.

2.4 Score Counter System
On-screen display showing:
Collected coins
Total coins
Real-time score update.

2.5 Win Condition
Game ends successfully when:
All coins are collected.
Victory message displayed.
Option in games like restart or return.

2.6 Camera System
Third-person follow camera or fixed camera.
Camera smoothly follows the player.
Camera avoids clipping through objects.

2.7 Level System 
CoinQuest 3D implements a three-level difficulty system to increase gameplay challenge gradually and demonstrate advanced scene management in a 3D environment.
Levels Included:
Level 1 – Easy


Level 2 – Intermediate


Level 3 – Hard


Each level is designed to be more difficult than the previous one through changes in environment complexity, coin placement, time constraints, and gameplay mechanics.

Level 1: Easy Mode
Designed for new players to understand basic controls and gameplay mechanics.
Features:
Small and simple 3D map


Fewer coins to collect


Static obstacles only


Wide open spaces


Longer time limit


Slower player movement speed


All cheat modes enabled


Goal:
Learn movement, camera control, and coin collection.



Level 2: Intermediate Mode
Introduces moderate difficulty and requires better navigation and timing.
Features:
Medium-sized map


Increased number of coins


Narrow pathways and walls


Combination of static and moving obstacles


Reduced time limit


Moderate player speed


Limited use of cheat modes (optional)


Goal:
Improve navigation skills and strategic movement.


Level 3: Hard Mode
Provides the highest challenge and tests player skill and precision.
Features:
Large and complex 3D map


Maximum number of coins


Tight spaces and vertical platforms


Fast-moving or rotating obstacles


Short time limit


Increased gravity effect


Reduced visibility (fog or dim lighting)


Cheat modes disabled or penalized (optional)


Goal:
Master advanced movement and efficient coin collection.



Level Progression System
The player can select any of the level from the menu EASY,MEDIUM AND HARD
Player can play each level and after reaching the destination the level will be over and gradually in each level the player has to face more challenges.
Player can quit the game anytime
Progress is saved until the gamer quit the game.




Level Completion Criteria
A level is considered complete when:
All coins in the level are collected within the time limit.



Final Win Condition
The game ends successfully when the player completes Easy, Intermediate, and Hard levels.


A final level completed text will be shown on the screen.


2.8 Level Timer System
Each level includes a countdown or stopwatch timer.
Features:
Timer starts when the level begins.


Player must collect all coins before time runs out.


Remaining time contributes to bonus score.


Timer displayed on screen in real time.


Fail Condition:
If time reaches zero → Level Failed
If the health score decreses then level will be failed


Option to retry the level.




2.9 Dynamic Obstacles System 
Levels contain moving or interactive obstacles.
Types of Obstacles:
Moving walls





rotating blocks


Behavior:
Obstacles move using transformation matrices.


Collision detection affects player movement.




2.10 Health & Damage System 
Player now has a health bar.
Features:
Player starts with fixed health (e.g., 100 HP).


Health decreases when:


Player hits obstacles






Game Over Condition:
Health reaches zero or negative→ Game Over


Option to restart level or entire game.


Adds realism and basic gameplay challenge.

2.11 Level Completion Screen 
After completing a level, a summary screen is displayed.
Displays:
Coins collected


Time taken


Bonus score


Cheats used (optional)


Options:
Back to the menu


Restart level



 Demonstrates UI overlay and game state management.


3. Cheat Mode Features
Cheat modes are intentional gameplay features for experimentation and demonstration.

3.1 Fly Mode
Player can move freely in all directions.
Gravity is disabled.
Useful for quick coin collection or testing.
Activation Key: F

3.2 Speed Boost
Increases player movement speed.
Helps reach distant coins faster.
Activation Key: Q

3.3 No-Clip Mode
Player can pass through walls and obstacles.
Collision with environment disabled.
Coin collision remains active.
Activation Key: V
3.4 Infinite Jump
Player can jump unlimited times.
Removes jump cooldown and gravity effect.
Activation Key: J

3.5 Coin Magnet Mode
Nearby coins automatically move toward the player.
Demonstrates object attraction logic.
Activation Key: M

3.6 Reveal All Coins
Highlights all remaining coins.
Helps locate hidden coins easily.
Activation Key: H

4. Controls Summary
Key
Action
W / S
Move Forward / Backward
A / D
Move Left / Right
Space
Jump
Mouse
Camera Look
F
Fly Mode
Q
Speed Boost
V
No-Clip
J
Infinite Jump
M
Coin Magnet
H
Reveal Coins
R
Restart Game
ESC
Pause




