This project is a classic Tic-Tac-Toe game implemented in Python using the pygame library. It features a single-player mode where you can play against an AI opponent that uses the Minimax algorithm to make optimal moves. The game is simple, fun, and a great way to understand how AI decision-making works in board games!

📂 Project Files:

runner.py: This is the main game runner that handles the game's graphical interface using pygame. It allows the player to choose between playing as X or O, and manages the game loop, user input, and rendering of the game board.

tictactoe.py: This file contains the core logic of the Tic-Tac-Toe game. It includes functions for:

Managing the game state (initial_state, player, actions, result).

Determining the winner (winner, terminal, utility).

Implementing the AI's decision-making using the Minimax algorithm (minimax, max_value, min_value).

🎯 Features:

🎨 Interactive GUI: The game has a clean and simple graphical interface built with pygame.

🤖 AI Opponent: Play against an AI that uses the Minimax algorithm to ensure it never loses!

🔄 Play Again: After the game ends, you can easily restart and play again.

🎲 Player Choice: Choose to play as X or O at the start of the game.

🛠️ How It Works:

The game starts by prompting the player to choose between X or O.

The player and AI take turns making moves on the 3x3 grid.

The AI uses the Minimax algorithm to determine the best possible move, ensuring it either wins or forces a tie.

The game ends when either a player wins or the board is full (tie).

🚀 How to Run:

Make sure you have pygame installed. You can install it using pip:


pip install pygame

Run the runner.py file to start the game:


python runner.py

🌟 Why This Project?

Learn AI Basics: Understand how the Minimax algorithm works in a simple game setting.

Practice Python: Great for practicing Python programming, especially with libraries like pygame.

Fun and Educational: A perfect blend of fun and learning, especially for those interested in game development or AI.

📸 Screenshots:

![image](https://github.com/user-attachments/assets/d4936a99-3189-4c10-9518-2d06901e8115)


![image](https://github.com/user-attachments/assets/0cb64562-bedd-4a9a-8b5d-b7e2fe9854c9)


![image](https://github.com/user-attachments/assets/ce64dd35-383c-4427-8f7a-9957021093e3)
