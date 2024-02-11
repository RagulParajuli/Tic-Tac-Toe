### Here's a breakdown of the provided Android project in bullet points:

# Player Representation:
  Players are represented by 0 (X) and 1 (O).
Empty cells are represented by 2.

# Game Initialization:
  The initial state of the game is set up with a 3x3 grid.
The game state is tracked using the gameState array.
Winning combinations are defined in the winPositions array.

# PlayerTap Method:
  Handles the player's tap on a cell.
Checks if the game is still active; if not, resets the game.
Updates the cell with the player's symbol (X or O) and switches the active player.
Animates the symbol's appearance.
Checks for a win or draw using the winPositions array.
Updates the status bar with messages for win, draw, or player turn.

# isDraw Method:
  Checks if the game is a draw by examining the game state for empty cells.
  
# updateStatus Method:
  Updates the status bar with the provided message.
  
# gameReset Method:
  Resets the game state, active player, and UI elements.
Updates the status bar to "Tap to Play."

# onCreate Method:
  Sets up the initial view when the activity is created, using the activity_main.xml layout file.

# Layout:
  The layout includes a 3x3 grid of cells represented by ImageViews and a TextView for the status bar.

# UI Elements:
  Uses ImageView for each cell and TextView for the status bar.

# Animation:
  Animates the appearance of X or O when a player taps on a cell.

# Game Active Flag:
  The gameActive boolean flag is used to control whether the game is still active or has concluded.

# Winning Announcement:
  Displays a message indicating the winner (X or O) or declares a draw.
Overall, the project provides a functional and interactive Tic-Tac-Toe game for two players on an Android platform, featuring a simple user interface and game logic.

## Some of the sample Screensots of app:
<img src="https://github.com/RagulParajuli/Tic-Tac-Toe/assets/117198787/9fd22499-31d0-4fb7-a5e4-491ceba3f52c" height="400" width="200"/>
<img src="https://github.com/RagulParajuli/Tic-Tac-Toe/assets/117198787/f9fce2d2-d173-40da-aa5e-7c4772b40616" height="400" width="200"/>
<img src="https://github.com/RagulParajuli/Tic-Tac-Toe/assets/117198787/ab28b867-ff25-4d36-b98e-da0a285f66b4" height="400" width="200"/>
<img src="https://github.com/RagulParajuli/Tic-Tac-Toe/assets/117198787/627a0496-a275-4c48-97db-250ad7b279e3" height="400" width="200"/>
