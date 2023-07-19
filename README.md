# Fortune-spin
"Fortune Spin: Test Your Luck and Win Big in this Exciting Slot Machine Adventure!"

# Slot Machine Game

This is a simple command-line slot machine game implemented in JavaScript. The game allows players to place bets, spin the reels, and potentially win prizes based on matching symbols.

## How to Play

1. Run the game by executing the JavaScript file in a Node.js environment.

2. At the start of the game, you will be prompted to enter the deposit amount, which represents the initial balance you have to play with.

3. You will then be asked to enter the number of lines you want to bet on (1-3). Each line represents a chance to win.

4. Next, enter the bet amount per line. Make sure the bet is within the allowed range and does not exceed your available balance.

5. The reels will spin and stop, revealing a random arrangement of symbols.

6. The symbols will be displayed in a grid format, showing the arrangement of symbols across rows.

7. If any of the lines have a matching combination of symbols, you will win a prize based on the symbol value and your bet amount.

8. The winnings will be added to your balance, and the updated balance will be displayed.

9. If your balance reaches zero, the game will end, and you will be notified that you have run out of money.

10. You will be given an option to play again. Enter 'y' to play again or 'n' to exit the game.

## Game Rules

- The game has 3 rows and 3 columns, forming a 3x3 grid of symbols.

- The available symbols and their respective counts are predefined.

- Each symbol has an assigned value that determines the prize amount if a winning combination is achieved.

- You can bet on 1 to 3 lines. Each line represents a separate chance to win.

- The bet amount per line should be within the range of your available balance and should not exceed it.

- A winning combination occurs when all symbols on a line match.

- The winnings are calculated by multiplying the bet amount per line by the value of the matching symbol.

## Dependencies

- This game requires the Node.js runtime environment to run.

- The `prompt-sync` package is used for synchronous user input in the command line. It is a dependency of the game and will be installed automatically when running the game.

## Getting Started

1. Clone the repository to your local machine.

2. Make sure you have Node.js installed on your machine.

3. Open a terminal or command prompt and navigate to the project directory.

4. Run the game by executing the following command:

   ```shell
   node slot-machine.js
   ```

5. Follow the on-screen instructions to play the game.

Enjoy playing the slot machine game and try your luck to win big!
