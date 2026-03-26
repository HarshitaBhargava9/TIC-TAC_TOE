"# TIC-TAC-TOE" 
🎮 Tic Tac Toe Game in C
A simple and fun Tic Tac Toe game built in the C programming language where you (the player) play against the computer.
The game runs in the terminal and uses basic C concepts like arrays, loops, and conditionals — perfect for beginners!

🧠 Features
👨‍💻 Single Player Mode – Play against the computer.
🧩 Smart Move Logic – Computer picks random available cells.
🎲 Automatic Winner Detection – Checks all rows, columns, and diagonals.
💬 Friendly Console Interface – Includes instructions, input prompts, and victory messages.
🕹️ Replay Anytime – Quick and lightweight, no external libraries needed.
🧩 How It Works
The game uses a 3x3 board represented by a 2D array.
The player uses ‘X’ and the computer uses ‘O’.
Turns alternate until one wins or the board is full (a tie).
The game declares the winner or a draw message at the end.
Code Overview
Function	Description
resetBoard()	Clears the game board before each new game
printBoard()	Displays the board in a 3×3 grid
checkFreeSpaces()	Checks how many empty cells are left
playerMove()	Gets the player's move from input
computerMove()	Makes a random valid move for the computer
checkWinner()	Determines if someone has won
printWinner()	Prints the result message (win/lose/tie)
⚙️ Compilation and Execution
🖥️ On Windows (using GCC in Command Prompt or PowerShell)
gcc Game.c
./a.exe

🧾 Example Gameplay

****************************************************
         Welcome to the Tic Tac Toe game!
****************************************************

* Instructions

    Player 1 sign = X
    Player 2 sign = O

Enter row #(1-3): 1
Enter column #(1-3): 2

 X |   |  
---|---|---
   |   |  
---|---|---
   |   |  

Computer moves...

 X |   | O
---|---|---
   |   |  
---|---|---
   |   |  