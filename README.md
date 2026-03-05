# Tic-Tac-Toe (C++)

A simple console-based Tic-Tac-Toe game written in C++.
The game supports multiple difficulty levels (Easy, Normal, Hard) and runs directly in the terminal.

---

## 📦 Requirements

To run this project you need:

* A C++ compiler that supports C++17 or later

  * **Windows:** MinGW (g++), MSVC (Visual Studio)
  * **Linux:** g++
  * **macOS:** clang++
* A terminal / command prompt

---

## 🚀 Getting Started

### 1. Clone the repository

Open a terminal and run:

```bash
git clone https://github.com/Gabbemannen00/TicTacToeExtended.git
cd tictactoe
```

---

### 2. Compile the program

#### Option A: Using g++ (MinGW / Linux / macOS)

```bash
g++ -std=c++17 -o tictactoe main.cpp
```

If your project consists of multiple `.cpp` files:

```bash
g++ -std=c++17 -o tictactoe *.cpp
```

---

#### Option B: Using MSVC (Visual Studio Developer Command Prompt)

```bat
cl /std:c++17 main.cpp
```

If you have multiple source files:

```bat
cl /std:c++17 *.cpp
```

---

### 3. Run the game

#### On Windows:

```bat
tictactoe.exe
```

#### On Linux / macOS:

```bash
./tictactoe
```

---

## 🎮 How to Play

* The game is played on a 3x3 grid.
* You play as **X** and the computer plays as **O**.
* Choose a difficulty level at the start of the game:

  * **Easy:** Random moves
  * **Normal:** Basic strategy
  * **Hard:** Optimal play (unbeatable)
* Enter your move by typing a number corresponding to a board position.

Example board layout:

```
 1 | 2 | 3
---+---+---
 4 | 5 | 6
---+---+---
 7 | 8 | 9
```

Type a number (1–9) and press Enter to place your move.

---
