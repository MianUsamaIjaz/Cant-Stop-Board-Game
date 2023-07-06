# 🎮 Cant Stop Board Game

The Cant Stop Board Game is a Java-based implementation of the popular board game "Can't Stop." It provides a digital version of the game, allowing players to enjoy the gameplay on their computers.

**Note: Due to academic reasons, the Java source files for this project could not be uploaded to the repository.**

**If you are unaware of how to play this game, please click the **Read Instructions** button inside the game, or visit https://youtu.be/VUGvOQatVDc for in-depth details of how to play this game.**

## 🌟 Features

- **Turn-Based Gameplay**: Players take turns rolling dice and making strategic decisions to advance on the game board.
- **Multiple Players**: Supports multiple players, allowing for competitive gameplay with friends or AI opponents.
- **AI Difficulty Levels**: Includes Easy and Hard AI opponents. The Easy AI takes actions randomly 50% of the time, while the Hard AI always takes 2 turns, selecting the sequence of numbers to avoid busting.
- **Color Deficiency Feature**: Provides a color palette based on the [colorblindness simulator](https://davidmathlogic.com/colorblind/#%23D81B60-%231E88E5-%23FFC107-%23004D40) to accommodate players with color deficiency. The color deficiency option can be selected during game setup.
- **Set-Up Menu**: Fully implemented set-up menu allowing players to view instructions, save the game, load a saved game, roll the dice, and more.
- **Accurate Game Logic**: The game accurately records players' points, locks out columns already claimed by players, and includes them in the potential busting logic.
- **Game End Detection**: Accurately determines when the game ends and closes the game afterwards.

## 🛠️ Technologies Used

The Cant Stop Board Game is built using the following technologies:

- **Java**: A versatile and widely-used programming language for building applications.
- **Object-Oriented Programming**: Utilizes object-oriented principles for organizing code and implementing game logic.
- **Swing**: A Java GUI toolkit for creating graphical user interfaces.
- **Git**: Version control system for tracking changes and collaborating on the project.
- **GitHub**: Hosting platform for storing and sharing the project repository.

## 🚀 Getting Started

To run the Cant Stop Board Game locally, just download this project's zip file. Extract it any where you want and open **Cant Stop Game.jar** file to run the game.

**Note: Please make sure that all the files including images are in the same folder!**

## 💻 Gameplay

- Players take turns rolling four dice and grouping them into two pairs to form their moves.
- After each roll, players can choose to advance on the game board by combining the values of their dice.
- The goal is to reach the top of three columns on the board by successfully advancing on each column.
- Players can strategically choose when to end their turn or continue rolling dice to increase their progress.
- The first player to reach the top of three columns wins the game.


## ✅ Objectives Accomplished:

  - The set-up menu for the game is fully implemented, along with all actions able to be taken by the user (this includes but is not limited to viewing the
    instructions, saving the game, loading the game, rolling the dice, etc...)
  
  - Both levels of difficulty for the AI, Easy and Hard. Easy AI takes actions randomly 50% of the time. Hard AI always takes 2 turns, and it
    will always pick the sequence of numbers so it does not bust according to the issue stated above, so the AI will (almost) never bust during the game.
  
  - Color deficiency feature was added using a color palette according to this link: https://davidmathlogic.com/colorblind/#%23D81B60-%231E88E5-%23FFC107-%23004D40.
    Color deficiency option can be selected during the set-up of the game.
  
  - The game accurately records the points a player has, locks out columns which are already claimed and includes them in potential busting logic, and accurately
    determines when the game ends and closes the game afterwards.

## 📝 Important Notes:

  - There is currently an issue with player tiles overlapping with each other. At the moment the color of a player who have recently taken a turn will be displayed     on the top. But it stores the colors on the specific location so it makes no difference in functionality of the game.
  
  - For the testing purposes of the game, you can roll the dices many times during a turn, while in real life it should be only one roll per turn.
  
## 👥 Teammates

- Teammate 1:
  Ijaz, Mian Usama (myself)

- Teammate 2:
  Pickett, Julian Christopher

- Teammate 3:
  Ahsan, Sarwar

- Teammate 4:
  Nahid, Mehedi Hasan

- Teammate 5:
  Haque, S M Ridwanul
