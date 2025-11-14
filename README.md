
# **Chess**

Pygame Chess is a fully playable chess game built using **Python** and **Pygame**. The goal of the project was to recreate the classic game with smooth piece movement, legal move validation, turn-based gameplay, and visually clean board rendering. It runs locally and lets you play chess against another human on the same device.

---

## **About the Project**

I built this project to learn more about building board games, handling game loops, and implementing move logic in Pygame. Chess is an interesting challenge because of the different movement rules for each piece, checks, castling, promotions, and turn management.

This project implements the core mechanics needed to play a real chess match on your computer, using Pygame for graphics and input handling.

---

## **Features**

* Standard 8×8 chessboard
* Drag-and-drop or click-to-move piece handling
* Turn-based gameplay
* Legal move validation for all pieces (pawn, rook, knight, bishop, queen, king)
* Detects checks, checkmates, and stalemates
* Pawn promotion
* Move highlighting (optional depending on your version)
* Smooth Pygame rendering

---

## **Tech Stack**

* **Python**
* **Pygame**
* Basic OOP for board + piece logic

---

## **Project Structure**

```
PygameChess/
│── chess.py                # Main game loop + rendering
│── board.py                # Board representation + rules
│── pieces.py               # Piece classes and movement logic
│── assets/                 # Piece images (PNG files)
│── utils.py                # Optional helpers
│── README.md
```

*(If your structure is different, tell me — I’ll adjust it.)*

---

## **How to Run the Game**

1. Install Pygame:

   ```bash
   pip install pygame
   ```

2. Run the game:

   ```bash
   python chess.py
   ```

3. The board will open in a Pygame window, and you can start playing.

---

## **Gameplay**

* White always starts
* Click or drag pieces to move
* Illegal moves are blocked
* Game ends on checkmate or stalemate
* Close the window to quit the game

---

## **Why I Built This**

This project helped me practice:

* Pygame event loops
* Handling 2D graphics
* Object-oriented programming
* Implementing game rules and logic
* Coordinating visuals and backend movement rules

Chess is a great test of both logic and game-design skills, so it made for a fun and challenging build.

---

## **Future Improvements**

* Add an AI opponent (Minimax)
* Add move history & notation
* Add sound effects
* Add timer for each player
* Add online multiplayer
* Add animations for piece movement


