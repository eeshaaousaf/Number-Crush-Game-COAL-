<div align="center">

# Number Crush Game

### Console-Based Match-3 Puzzle Game in x86 Assembly Language

<img src="https://img.shields.io/badge/Assembly-x86-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Irvine32-Library-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/Platform-Windows-success?style=for-the-badge" />
<img src="https://img.shields.io/badge/Project-COAL-purple?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />

</div>

---

# Overview

**Number Crush Game** is a console-based interactive puzzle game developed using **x86 Assembly Language** with the **Irvine32 library**.

The project is inspired by popular match-based puzzle games like **Candy Crush**, but implemented entirely using low-level programming concepts such as:

- Array manipulation
- Register operations
- Memory addressing
- Stack operations
- Conditional branching
- Procedures & macros

The game contains multiple difficulty levels, score tracking, bomb mechanics, and file handling for persistent player records.

---

# Objectives

The main objectives of this project are:

- Develop a fully functional match-3 puzzle game in Assembly Language
- Implement array indexing and memory manipulation
- Apply low-level game logic using registers and procedures
- Create combo detection and scoring systems
- Implement randomized board generation
- Store player records using file handling
- Strengthen understanding of:
  - Loops
  - Procedures
  - Macros
  - Stack Operations
  - Conditional Branching

---

#  Game Features

 Three dynamic difficulty levels  
 Colored console game board using Irvine32  
 Match-3 row and column combo detection  
 Bomb explosion mechanics  
 Blocked cells in advanced levels  
 Random board generation  
 Valid move checking  
 Automatic move reversal if no combo occurs  
 Real-time score calculation  
 Player name input  
 File handling for record storage  
 Highest score tracking  

---

#  Gameplay Rules

- Only adjacent swaps are allowed
  - Up
  - Down
  - Left
  - Right
- Diagonal swaps are not allowed
- Bomb-to-bomb swaps are invalid
- Block cells (`X`) cannot be swapped
- A valid move must create at least 3 matching numbers
- Invalid moves are automatically reversed
- Bomb explosions remove all matching elements
- Every crushed number increases the score
- Each level allows only **2 valid moves**

---

#  Game Levels

##  Level 1

| Feature | Description |
|---|---|
| Board Size | 10 × 10 |
| Elements | Numbers (1–5) + Bombs (B) |
| Difficulty | Beginner |

Purpose:
- Introduces basic gameplay and combo logic

---

##  Level 2

| Feature | Description |
|---|---|
| Board Size | 9 × 9 |
| Elements | Numbers (1–4), Bombs, Empty Spaces |
| Difficulty | Intermediate |

Purpose:
- Adds obstacles and restricted movement

---

##  Level 3

| Feature | Description |
|---|---|
| Board Size | 10 × 10 |
| Elements | Numbers, Bombs, Block Cells (X) |
| Difficulty | Advanced |

Purpose:
- Introduces blocked cells and higher complexity

---

#  Functional Workflow

```text
Start Game
    ↓
Display Welcome Screen
    ↓
Player Enters Name
    ↓
Generate Random Board
    ↓
Player Makes Valid Moves
    ↓
Combo Detection & Crushing
    ↓
Bomb Handling
    ↓
Score Calculation
    ↓
Save Results to File
    ↓
Load Next Level
    ↓
Display Final Results
```

---

#  Core Concepts Used

This project demonstrates practical implementation of:

- 2D Arrays
- Memory Addressing
- Register Manipulation
- Procedures
- Macros
- Conditional Logic
- Looping Structures
- Stack Operations
- File Handling
- Random Number Generation

---

#  Data Structures Used

| Structure | Purpose |
|---|---|
| 2D Array (10×10) | Level 1 & 3 Boards |
| 2D Array (9×9) | Level 2 Board |
| Variables | Score, Moves, Level |
| Text File | Player Record Storage |

---

#  File Handling

The project maintains a file named:

```text
PlayersRecord.txt
```

Stored Information:

- Player Name
- Level 1 Score
- Level 2 Score
- Level 3 Score
- Highest Score

This ensures persistent storage even after program termination.

---

#  Input & Output

## Input

- Player name
- Swap coordinates/indexes

## Output

- Colored game board
- Score updates
- Move validation messages
- Combo crushing messages
- Bomb explosion notifications
- Final score records

---

#  Technologies Used

| Category | Technology |
|---|---|
| Language | x86 Assembly Language |
| Library | Irvine32 |
| Platform | Windows |
| IDE | Visual Studio / MASM |
| Concepts | COAL (Computer Organization & Assembly Language) |

---

#  Project Structure

```bash
Number-Crush-Game/
│
├── src/
│   ├── main.asm
│   ├── game_logic.asm
│   ├── levels.asm
│   ├── bomb_logic.asm
│   └── file_handling.asm
│
├── assets/
│   └── screenshots/
│
├── data/
│   └── PlayersRecord.txt
│
├── docs/
│   └── Project_Report.pdf
│
├── Irvine/
│   └── Irvine32.inc
│
├── README.md
└── LICENSE
```

```bash
git clone https://github.com/your-username/Number-Crush-Game.git
```

3. Open the project in Visual Studio
4. Build and run the `.asm` file

---

#  License

This project is developed for academic and educational purposes.

---


<div align="center">

</div>
