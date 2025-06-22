# ♟️ AI-Powered Chess Strategy Engine

An interactive chess game developed using **Python**, **Pygame**, and **AI algorithms** like Minimax and Alpha-Beta Pruning. This project offers strategic gameplay against a smart AI opponent through a user-friendly GUI.

---

## 🚀 Features

- 🤖 **AI-Driven Moves**: Implements **Minimax** and **Alpha-Beta Pruning** to make challenging and intelligent moves.
- 🕹️ **Interactive GUI**: Built with **Pygame**, providing a smooth user experience and clear visuals.
- ♟️ **Full Chess Logic**: Includes rules for all standard chess moves (castling, en passant, check, checkmate, etc.).
- 🔄 **Turn-Based Gameplay**: Supports human vs AI gameplay with proper turn handling and move validation.
- 🎯 **Smart Strategy**: AI evaluates game states and picks the best available moves based on depth-limited tree search.

---

## 🛠️ Technologies Used

- **Python 3**
- **Pygame**
- **Minimax Algorithm**
- **Alpha-Beta Pruning**

---

## 📁 File Structure

```
AI-Powered-Chess-Engine/
│
├── img/               # Images used for pieces or UI
├── AI.py              # Minimax and Alpha-Beta logic
├── LICENSE            # License file
├── README.md          # Project documentation
├── board.py           # Chess board representation and functions
├── chess.py           # Main game runner
├── piece.py           # Classes for each chess piece
├── requirements.txt   # Python dependencies
├── settings.py        # Game settings and configurations
├── tile.py            # Tile handling logic for the board
└── timer.py           # Chess timer and clock logic
```

---

## 📦 Installation & Running

### 1. Clone the repository
```bash
git clone https://github.com/your-username/AI-Powered-Chess-Engine.git
cd AI-Powered-Chess-Engine
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the game
```bash
python chess.py
```

---

## 🎮 Controls

- **Click** on a piece to select.
- **Click** on a valid tile to move.
- Game enforces chess rules, including turn-based logic and checkmate detection.

---

## 🧠 AI Strategy

- The AI uses the **Minimax** algorithm with **Alpha-Beta pruning** to evaluate potential game states.
- Evaluation function balances material, positioning, and check status.
- Depth of search can be tuned for difficulty scaling.


