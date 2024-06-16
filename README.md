# Tic Tac Toe Game in Java

In this Tic-Tac-Toe game, you'll see the approach to implement the game in Java. In this game, two players play on a 3x3 grid. Players take turns selecting X or O for specific box numbers. For example, if you select a number, X or O will be displayed on the board, and the next turn will be taken. The task is to create a Java program to implement a 3x3 Tic-Tac-Toe game for two players.

## Game Overview

The game is played on a 3x3 matrix. One player plays 'X' and the other plays 'O'. Players select the boxes where they want to place their chosen character. To place them, the player enters a number from '1' to '9' corresponding to the 3x3 matrix. The game continues using if-else statements. If any player manages to align their characters in a row, column, or diagonal, that player wins. If neither player achieves this, the game ends in a draw.

## Program Details

### Class and Method Descriptions

#### tictac.java

- **Class:** tictac
- **Method:** `checkWinner` - Decides the winner based on the 3x3 grid. Uses switch case statements for possible win combinations and if-else condition for draws.
- **Variables:** 
  - `board` - Array representing the 3x3 grid.
  - `turn` - Tracks which player's turn it is.
  - `numInput` - Takes input from the user for their move.

### Game Flow

1. **Initialization:** 
   - A class named `tictac` is created.
   - The `board` array is initialized to represent the 3x3 grid.
   - The `turn` variable is set to "X" initially.

2. **Game Loop:**
   - The game prints the initial board.
   - Players take turns entering numbers from 1 to 9 to place their markers.
   - The `checkWinner` method checks if there's a winner or if the game is a draw.
   - If an invalid input is given, an error message is displayed, and the player is prompted to enter again.

3. **End of Game:**
   - If a player wins, a congratulatory message is displayed.
   - If the game is a draw, a draw message is displayed.

### How to Run

To run the Tic Tac Toe game, compile and execute the `tictac.java` file. Ensure that the Java Development Kit (JDK) is installed on your system.

```sh
javac tictac.java
java tictac
```

<div align="center">

  ![1](https://imgur.com/I8h22P8.png)
  
  ![2](https://imgur.com/tZdSCaQ.png)

</div>
