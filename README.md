# Super-Mario-Clone
This project is a game made using the MonoGame framework and written using C#. This game is a platformer based on the Super Mario Bros franchise. You play as Mario and make your way through a series of 3 levels. You must complete a level to move onto the next.

The game features 4 enemy types: Goombas, Koopa Troopas, Para Koopas, and Piranha Plants. They all damage Mario upon collision from the front or back, but both forms of Koopas will turn into a shell upon collsion with Mario from the top. Goombas and Koopas walk forward until they collide with an obstacle, which causes them to turn around and walk in the opposite direction until they collide with another obstacle. Para Koopas fly in an up and down motion until Mario collides with them from the top, which turns the Para Koopa into a traditional Koopa Troopa. The Piranha Plant will occasionally pop out of a few select pipe obstacles and stay there for a few seconds before retreating back into the pipe.

The game features 5 power up types: Red Mushroom (turns small Mario into big Mario), Green Mushroom (gives Mario another life), Fire Flower (gives Mario the power to throw fire ball projectiles), Feather (gives Mario the ability to jump high and glide downwards), and Balloon (gives Mario the ability to float up and down). Power ups can be collected by hitting a Question Block from the bottom, which will spawn a powerup above said block. Mario must then collide with the power up to get its bonus. Upon collision with the Question Block, Red Mushrooms will move in the direction of Mario, Green Mushrooms will move in the opposite direction of Mario, and Feathers will fly upwards and then gradually make their way back down to the ground.

In addition to the Question Block previously mentioned, there are also Coin Blocks, which will pop out a coin when hit from the bottom, some of which can be hit up to 10 times to collect coins. Additionally, there are Spike Blocks which damage Mario if collided with, and some static stone blocks that can be used to build walls or stairs.

A few statistics are recorded and displayed on the HUD. The number of coins Mario collects, how many lives Mario has, and the number of points collected are all recorded and shown in the HUD. Each coin collected adds 200 points to the points counter, each enemy killed adds 100 points, and each power up (except the Green Mushroom) adds 1000 points. There is also a timer that tells the player how much time left they have to complete the level. The player has 400 seconds to complete a level.

The controls to play are as follows: 
- A key -- left movement
- D key -- right movement
- W key -- jump
- S key -- crouch
- Space bar -- shoot projectiles (fire balls)
- Shift key -- sprint

To use the Feather power up, sprint using the Shift key, A key or D key to move in the desired direction, and jump using the W key when at full sprint speed. Hold all keys to go the furthest distance.

## Installation Instructions
Steps:
1. Install Visual Studio if not already installed on computer (I have only tested with VS 2019 so I cannot confirm if it would work on any other versions). Visual Studio can be acquired here: https://visualstudio.microsoft.com/vs/older-downloads/
2. Clone this repository to a desired directory on your computer.
3. Inside the "Super-Mario-Clone" folder, open the "Mario.sln" file. This will open Visual Studio.
4. Run the game by clicking the Play button at the top of the window.

Note: Check the issues tab. There is currently an issue in the repo that is preventing the game from being run.

## Credits
This project was contributed to by Matthew Manning (https://github.com/matt-manning), Oskar Klear (https://github.com/oskarklear), Kyle Shin, Daniel Jones, and Bennett Palmer.
