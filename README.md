# Eater Game

## Overview

This is a simple console-based implementation of the Eater game for two players, Passer and Eater. The game is played on an m\*m grid board, where players take turns placing markers of their own color. The goal of the Passer is to form a connected path of its markers from the top to the bottom, while the Eater aims to prevent this or win if the board is full.

## Getting Started

To run the game, compile the C code using a C compiler, such as gcc:

```bash
gcc "Passer and Eater Game.c" -o eater_game
```
Then, run the executable:
 
 ```bash
./eater_game
```

Follow the on-screen instructions to play the game.

## Features

1. **Display Game Board:**
   - The game board is displayed in text format. Red markers (P) represent the Passer's moves, and blue markers (E) represent the Eater's moves.

2. **Accept Players' Moves:**
   - Players take turns entering their moves by specifying the row and column where they want to place their marker.

3. **Terminate Game:**
   - The game terminates when either the Passer wins by forming a connected path from top to bottom or when the board is full with no connected path for the Passer.

4. **Computer Player:**
   - There is a basic computer player that randomly selects valid moves.

5. **Smart Computer Player:**
   - An advanced computer player is implemented with some level of intelligence. It considers the current state of the board and strategically selects moves to block the Passer or enhance its chances of winning.

## How to Play

1. Choose the size of the board (minimum 3x3).
2. Players take turns entering their moves.
3. The Passer wins if a connected path is formed from top to bottom.
4. The Eater wins if the board is full, and the Passer has no connected path.


## Future Improvements

- Implement additional strategies for the smart computer player to enhance its intelligence.
- Add error handling for user input to ensure valid moves.
- Optimize the code for better performance and readability.

Feel free to contribute to the project by submitting pull requests or reporting issues.
