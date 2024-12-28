# Tic-Tac-Toe

## Overview
Tic-Tac-Toe with a simple AI to play against. The game allows three modes:

- **Player vs. Player**: A classic two-player mode.
- **Player vs. AI**: Play against the AI.
- **AI vs. AI**: Watch two AIs battle it out (for fun!).

## Features
- **Three Modes**:
  - **Player vs Player (2-player mode)**
  - **Player vs AI (1-player mode)**
  - **AI vs AI (for fun)**
  
- **AI Logic**: The AI is programmed with optimal move logic to play Tic-Tac-Toe efficiently.
  

#### **Positions are similar to the number pad** on your keyboard!

### Instructions:
1. Choose your mode:  
   - **Player vs. Computer**
   - **Player vs. Player**
   - **Computer vs. Computer**

2. Enter player names (in Player vs. Player mode) and select whether you want to play as 'X' or 'O'.
   
3. The game board will be updated after every move, and the winner will be displayed.

---

## Code Walkthrough

### Functions

1. **default()**: Displays the welcome message for the game.
2. **rules()**: Displays the rules of the game, showing the board layout and explaining how to select positions.
3. **play()**: Asks the user if they are ready to play.
4. **names()**: Prompts the users to enter their names.
5. **choice()**: Asks players to choose their 'X' or 'O'.
6. **first_player()**: Randomly determines which player goes first.
7. **display_board()**: Displays the current state of the game board.
8. **player_choice()**: Prompts the player to choose a position on the board.
9. **CompAI()**: AI function to choose the best possible move based on the current game state.
10. **place_marker()**: Places a marker ('X' or 'O') on the board at the selected position.
11. **space_check()**: Checks if a position on the board is empty.
12. **full_board_check()**: Checks if the board is full, signaling a draw.
13. **win_check()**: Checks if a player has won the game.
14. **delay()**: Introduces a delay for AI moves in Player vs. AI and AI vs. AI modes.
15. **replay()**: Asks if the user wants to play again after the game ends.

---

## Steps to Run the Project

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/farhat-1203/Tic-Tac-Toe.git
    cd Tic-Tac-Toe
    ```
    
3. **Run the Script**:
    ```bash
    python tic-tac-toe.py
    ```

## Project Structure
```
├── tic-tac-toe.py          # Main script
├── README.md               # Project documentation
├── LICENSE                 # License file (MIT License)
```
