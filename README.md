# Chess Game

A sophisticated JavaScript chess implementation with intuitive gameplay and interactive board dynamics.

## 🎮 Features
- **Interactive Chess Board**: Dynamically colored squares with intuitive piece selection and movement.
- **Visual Feedback**: Highlighted squares show valid moves with pink for selected pieces and green for possible destinations.
- **Turn-Based Gameplay**: Clear indication of whose turn it is (White or Black).
- **Complete Movement Rules**: Accurate implementation of movement patterns for all chess pieces:
  - **Pawns**: First-move double step and diagonal capture.
  - **Rooks**: Horizontal and vertical movement.
  - **Bishops**: Diagonal movement.
  - **Queens**: Combines rook and bishop movements.
  - **Knights**: L-shaped movement.
  - **Kings**: Single square in any direction.
- **Win Detection**: Automatic detection of king capture with game-end notification.

## 🛠️ Technologies
- **Pure JavaScript**: Core game logic with DOM manipulation.
- **HTML**: Structure for the chess board.
- **CSS**: Styling for the game interface.

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/chess-game.git
   ```
2. Open `index.html` in your browser to start playing.

## 🎯 How to Play
1. Click on a piece to select it (turns pink).
2. Valid move destinations will highlight in green.
3. Click on a green square to move your piece.
4. The game alternates between White and Black turns.
5. Capture the opponent's king to win.

## 🔮 Future Enhancements
- Special moves (castling, en passant, pawn promotion).
- Game state persistence.
- Move history and notation.
- AI opponent.
- Multiplayer support.
