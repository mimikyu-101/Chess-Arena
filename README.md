# ♟️ Chess Arena — Human vs AI

> *“A classic game of minds, powered by Python, Minimax, and a touch of strategy.”*

Welcome to **Chess Arena**, a fully playable **GUI-based Chess game** where **you (White)** battle an **AI opponent (Black)** that thinks ahead, evaluates positions, and punishes mistakes.

Built from scratch using **Python + Tkinter**, this project focuses on **game logic, AI decision-making, and clean object-oriented design**.

---

## 🎮 Game Modes

- 🧑 **Human (White)** vs 🤖 **AI (Black)**
- Click-to-move **OR** type moves using chess notation (`e2e4`)
- Real-time validation of legal moves
- Automatic AI response after every move

---

## 🧠 AI Engine (Minimax + Alpha-Beta Pruning)

The AI isn’t random — it **thinks**.

### 🔍 AI Highlights
- Uses **Minimax algorithm** with **Alpha-Beta pruning**
- Configurable search depth (default: `3`)
- Evaluates:
  - ♞ Material advantage
  - ♚ King safety
  - 🎯 Center control
  - ⚠️ Check & Checkmate states
- Automatically detects:
  - Check
  - Checkmate
  - Game-ending positions

> *The AI sacrifices, defends, and attacks intelligently — just don’t underestimate it.*

---

## ♟️ Chess Rules Implemented

✔️ All standard piece movements  
✔️ Legal move validation  
✔️ Check detection  
✔️ Checkmate detection  
✔️ King safety enforcement  
✔️ Move rejection if king remains in check  

> Illegal moves are blocked before they happen — no cheating 😄

---

## 🖱️ Controls

### 🖱 Mouse Play
1. Click a **White piece**
2. Green dots highlight **valid moves**
3. Click destination square

### ⌨ Keyboard Input
Type moves in:
- `e2e4`
- `e2 e4`

Then press **Enter** or click **Make Move**

---

## 🎨 Graphical Interface

- Classic **8×8 chessboard**
- Unicode chess pieces (♔ ♕ ♖ ♗ ♘ ♙)
- Highlighted legal moves
- Coordinate labels (a–h, 1–8)
- Styled wooden-theme UI
- “🤖 AI is thinking…” indicator during AI calculations

---

## ⚙️ Tech Stack

- Language: Python 3
- GUI: Tkinter
- AI: Minimax + Alpha-Beta Pruning
- Design: Object-Oriented Programming
- Paradigms: Abstraction, Inheritance, Polymorphism

---

## 🏁 Win Conditions

- ♔ Checkmate → Game ends immediately
- ⚠️ Check → Warning displayed
- Illegal moves → Blocked automatically

---

## 🛠️ Possible Future Upgrades

- ♜ Castling support
- ♟ Pawn promotion UI
- ⏱ Difficulty selector (AI depth)
- 🔁 Undo / Redo moves
- 🌐 Multiplayer support
- 📜 Move history panel

--- 

## 🧑‍💻 Author

Abdullah Nadeem
> Built as part of AI & game logic practice using classical algorithms.

## ⭐ If You Like This Project

Give it a ⭐ on GitHub
The AI gets stronger with encouragement 😉
