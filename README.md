# Chess

## Description

A chess game and a chess bot

Currently the program has one bot to play against. The bot uses a simple minimax algorithm to calculate ahead and evaluate the position. While I classified the bot level as "easy", it will punish you for hanging your pieces or checkmate. The bot uses approximately 3 seconds per move.

You can also play on your own, controlling both the white and the black pieces yourself.

## Requirements

- Python
- PyGame

## How to use

- To start the program, run the chess.py file in the folder Chess2025.
- Use the mouse click to select a game mode.
- To make a move, first click on the piece that you want to move. After the piece is highlighted in yellow, click on a square where you would like to move the piece. If you want to change the highlighted piece, click on the piece again or on any square where the highlighted piece cannot move.
- To castle, first click on your king to highlight it, and then click two squares to either side of the king.
- When promoting a pawn, the program will ask for keyboard input for what piece you want to promote to. Click on the console and then press the preferred key (Q, R, B, or K) and press Enter.
- The game ends when there is a checkmate or a stalemate on the board.
- You can always quit the program by clicking the X on the top right of the window.


## Progression

I started this project from scratch, and the first step was to make a functioning chessboard with all the pieces. I added logic that ensures that every move follows the rules of chess. This includes special rules such as castling, promoting a pawn, and en passant. I used PyGame to draw the board with the pieces. After the game was playable (controlling both white and black pieces myself), I started working on a chess bot. I added an evaluation function and a recursive minimax algorithm that searches for the best moves.

When first testing the bot, one main concern was high time complexity. If the minimax algorithm's depth was set too high, it would take hours to search for a best move, so for now, the bot only searches two moves ahead. To improve the bot's chess performance while keeping computation time relatively low, I will learn about and implement smarter search methods, for example, alpha-beta pruning, to cut down on the amount of computation needed. I will also work on how the evaluation function evaluates a chess position.

As the project progressed, the code started to get more unstructured. While I did utilize classes for implementing the movement rules for different chess pieces, there is more work to be done. I plan to refactor the code and utilize more classes to adhere to exemplary object-oriented programming principles. This will make the project easier to maintain in the long run.

During this project, I wish to learn more about programming and smart search algorithms but also broaden my understanding of chess. While learning about different search techniques, I plan to implement multiple chess bots with varying difficulty levels. My long-term goal is to make a bot better at chess than me while keeping it relatively fast (one move should not take more than 10 seconds).

