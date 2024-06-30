
# Tic Tac Toe Game in Python

Welcome to my Tic Tac Toe game, implemented in Python! This game is a classic, and I've added a twist by including an AI opponent for you to play against.

## How it Works

- The game is implemented in a single Python file, `game.py` The game board is represented as a dictionary called `slate`, where each key represents a position on the board (1-9) and the value is either '   ', ' X ', or ' O ', depending on whether the position is empty, occupied by the player, or occupied by the AI.

- The game starts with the player's turn. The player is asked to input a position to draw their 'X'. If the position is valid (i.e., within the range 1-9 and not already occupied), an 'X' is placed on the board at that position. The game board is then printed out for the player to see.

- Next, it's the AI's turn. The AI has a strategy to decide where to place its 'O'. It first checks if it can win in the next move. If it can't, it checks if the player can win in the next move and blocks it. If neither of these conditions is met, the AI chooses a random position to place its 'O'.

- The game continues in this way, alternating between the player and the AI, until either the board is full or there's a winner. The game checks for a winner after each move by calling the `check` function, which checks if there are three 'X's or 'O's in a row, column, or diagonal.

## Fun Features

- One of the fun features of this game is the AI opponent. It's not just placing 'O's randomly; it has a strategy. It can block your winning moves and make its own winning moves when possible. This makes the game more challenging and fun!

- Another cool feature is the game board display. After each move, the game board is printed out, showing the current state of the game. This makes it easy to see what's happening and plan your next move.

So, are you ready to take on the challenge? **Let's play Tic Tac Toe!**
