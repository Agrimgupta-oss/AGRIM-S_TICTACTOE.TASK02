Agrim's Tic Tac Toe | Advanced Game

This project is an advanced, futuristic-themed Tic Tac Toe game developed by Agrim. It features a responsive design, player vs. player and player vs. AI modes, score tracking, and interactive visual effects.

✨ Features

Player vs. Player (PvP) Mode: Play against another human opponent.
Player vs. AI (PvC) Mode: Challenge a simple AI opponent.
Score Tracking: Keeps track of wins for Player X, Player O, and draws.
Responsive Design: Optimized for various screen sizes.
Interactive UI:
Rainbow animated background.
Floating particle effects.
Ripple effect on cell clicks.
Winning cell animation.

Game Controls:

"New Game" button to reset the board.
"Reset Scores" button to clear all game statistics.
Modal Pop-up: Displays game results (win/draw) with a "Play Again" option.

🛠️ Technologies Used

HTML5: For the game structure.
CSS3: For styling, animations, and responsiveness.
JavaScript: For game logic, AI, and interactive elements.

🚀 How to Play

Open the File: Double-click MultipleFiles/Agrim's Tic Tac Toe .html in your browser.
Choose Game Mode: Select "Player vs Player" or "Player vs AI".
Start Playing: Click on the cells to make your moves.
Reset: Use the "New Game" button to start a fresh round or "Reset Scores" to clear all statistics.

🧠 AI Logic (Player vs AI Mode)

The AI (Player O) follows a simple strategy:
Win: Checks if it can win in the current turn.
Block: Checks if the opponent (Player X) can win and blocks them.
Center: Tries to take the center cell (index 4).
Corners: Attempts to take any available corner cells (indices 0, 2, 6, 8).
Random: Makes a random move if no strategic move is available.

📂 Project Structure

Run
Copy code
1.
2└── MultipleFiles/
3    └── Agrim's Tic Tac Toe .html  <-- The main game file
