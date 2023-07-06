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
  - There is currently an issue with player tiles overlapping with each other. At the moment the player color with the highest number (player 4 for example)
    will be displayed. Currently attempting to get multiple colors displayed at the same time.
  - The Command structure was not implemented due to delays caused by issues with the code. 
  - Selecting the difficulty for any human players will not affect the running of the game in any way.
  - The runner tiles being updated is done sequentially. This means the first two dice selected will be processed before the 3rd and 4th dice picked. This will
    result in the player busting if the first sequence results in a bust, even if the second sequence does not. Will be corrected by the presentation.
  
