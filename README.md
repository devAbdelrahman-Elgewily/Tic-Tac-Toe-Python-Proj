# 3D Tic-Tac-Toe AI (4x4x4)

This is a Python-based AI project for a 3D 4x4x4 Tic-Tac-Toe game, where a human can play against a computer that uses the **Minimax algorithm** enhanced with **Alpha-Beta Pruning** and **Heuristic Evaluation** for optimal gameplay.

## 🎯 Project Features

- **3D Board Support**: 4x4x4 Tic-Tac-Toe board structure (64 cells).
- **AI Engine**:
  - **Minimax Algorithm**: Strategic move decision-making based on recursion.
  - **Alpha-Beta Pruning**: Optimized search to reduce unnecessary evaluations.
  - **Heuristic Evaluation Function**: Intelligent move scoring when the full game tree cannot be searched due to complexity.
- **Human vs AI Gameplay** via the console.
- **Customizable Search Depth** for balancing difficulty and performance.

---

## 🧠 How the AI Works

The AI player uses the Minimax algorithm to explore possible future moves and evaluate them using a custom heuristic when the depth limit is reached. Alpha-beta pruning significantly improves efficiency by cutting off branches that won’t affect the outcome.

### Heuristic Highlights

The heuristic function scores the board based on:
- Potential winning lines (rows, columns, diagonals)
- Blocking opponent lines
- Depth to terminal state (faster wins preferred)

---

## 🛠️ Installation & Running the Game

### Prerequisites
- Python 3.7+

### Clone the Repository
```bash
git clone https://github.com/yourusername/3d-tictactoe-ai.git
cd 3d-tictactoe-ai
