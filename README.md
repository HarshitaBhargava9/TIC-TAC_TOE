# 🎮 Tic Tac Toe Game in C

A simple command-line Tic Tac Toe game built using C, where a player competes against the computer. The game features a clean interface, input validation, and basic AI (random moves).

---

## 🚀 Features

* 🧑 Player vs Computer gameplay
* 🎲 Computer makes random valid moves
* 🧠 Game logic for win/draw detection
* 📋 Clean 3x3 board display
* ⚠️ Input validation for invalid moves
* 🔁 Continuous gameplay until win or draw

---

## 🛠️ Tech Stack

* Language: **C**
* Libraries Used:

  * `stdio.h` → Input/Output operations
  * `stdlib.h` → Random number generation
  * `time.h` → Seeding randomness
  * `ctype.h` → Character handling

---

## 📦 How to Run

### 1️⃣ Compile the Code

```bash
gcc Game.c -o tic_tac_toe
```

### 2️⃣ Run the Program

```bash
./tic_tac_toe
```

---

## 🎯 How to Play

* The board is a **3×3 grid**
* You play as **X**
* Computer plays as **O**
* Enter row and column numbers (1–3) to make a move

### 🧾 Example Input

```
Enter row #(1-3): 1
Enter column #(1-3): 2
```

---

## 🧩 Game Flow

1. Board initializes empty
2. Player makes the first move
3. Computer makes a move
4. Game checks for:

   * Winner
   * Draw (no free spaces)
5. Loop continues until game ends

---

## 🏆 Winning Conditions

* Any row, column, or diagonal with the same symbol wins
* If all spaces are filled with no winner → **Draw**

---

## ⚠️ Error Handling

* Prevents overwriting occupied cells
* Ensures valid row and column input range (1–3)
* Handles full board (draw condition)

---

## 📌 Future Improvements

* Add smarter AI (Minimax algorithm)
* Multiplayer mode (Player vs Player)
* GUI version (using SDL / GTK)
* Score tracking system

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

* Fork the repo
* Improve logic/UI
* Submit a pull request

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 💡 Author

**Harshita Bhargava**

---

⭐ If you like this project, consider giving it a star!
