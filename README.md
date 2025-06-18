
# ♟️ Chess Game System in Java

This is a console-based chess game developed in Java, created as a hands-on project to apply the concepts of **Object-Oriented Programming (OOP)** learned throughout the course ["Java OOP"](http://educandoweb.com.br) by Prof. Dr. Nélio Alves.

The main goal of this project is to consolidate knowledge about OOP concepts, exception handling, data structures, and clean code practices by building a fully functional chess game that runs in the terminal.

---

## 🚀 Features

- ✅ Full chess game playable in the terminal  
- ✅ Chess rules implemented, including:
  - ✔️ Check  
  - ✔️ Checkmate  
  - ✔️ Castling (Kingside and Queenside)  
  - ✔️ En Passant  
  - ✔️ Pawn Promotion  
- ✅ Turn-based control with alternating players  
- ✅ Board visualization with colored pieces (white/black)  
- ✅ Display of possible moves for selected pieces  
- ✅ Captured pieces tracking  
- ✅ Defensive programming with custom exceptions  
- ✅ Clean screen between turns for better user experience  

---

## 🏗️ Object-Oriented Design

### ✔️ Main OOP Concepts Applied:
- Classes and Objects  
- Encapsulation  
- Inheritance  
- Polymorphism  
- Abstraction (abstract classes and methods)  
- Exception handling with custom exceptions  
- Layers architecture (UI layer, Chess layer, Board layer)  

---

## 🎯 Classes Overview

### 📄 **boardgame package**
- `Position`: Represents board coordinates (row and column)  
- `Board`: Manages pieces, positions, and board rules  
- `Piece`: Generic piece superclass  
- `BoardException`: Handles invalid board-related operations  

### ♟️ **chess package**
- `ChessMatch`: Main class to control game logic and flow  
- `ChessPiece`: Extends `Piece` with chess-specific logic  
- `ChessPosition`: Converts between chess notation (e.g., e4) and matrix positions  
- `ChessException`: Handles chess-specific errors  

#### Pieces Implemented:
- `King` (with castling logic)  
- `Queen`  
- `Rook`  
- `Bishop`  
- `Knight`  
- `Pawn` (with promotion and en passant)  

---

## 🖥️ How to Run

### ✔️ Prerequisites
- Java JDK 11 or later  
- IDE like IntelliJ, Eclipse, NetBeans, or terminal with Java installed  

### ✔️ Run the project
1. Clone the repository:  
```bash
git clone https://github.com/your-username/chess-game-java.git
```

2. Navigate into the project folder:  
```bash
cd chess-game-java
```

3. Compile the code:  
```bash
javac src/application/Program.java
```

4. Run the game:  
```bash
java -cp src application.Program
```

---

## 🎨 Terminal Colors

- White pieces → Uppercase letters  
- Black pieces → Lowercase letters with different color  

> ⚠️ Colors may depend on your terminal. Recommended to use Git Bash (Windows) or native terminal (Linux/Mac) for best visualization.

---

## 🚧 Implemented Rules

| Rule               | Status |
|--------------------|--------|
| Move validation    | ✅      |
| Turns and players  | ✅      |
| Check detection    | ✅      |
| Checkmate detection| ✅      |
| Castling           | ✅      |
| En Passant         | ✅      |
| Promotion          | ✅      |
| Captured pieces UI | ✅      |

---

## 📚 Concepts Covered

- ✅ OOP (Encapsulation, Inheritance, Polymorphism, Abstraction)  
- ✅ Exception Handling (BoardException, ChessException)  
- ✅ Defensive Programming  
- ✅ Data Structures (Matrix, Lists)  
- ✅ Clean Code Principles  
- ✅ Layered Architecture  

---

## 👨‍💻 Author

- **Guilherme Miranda**  
[LinkedIn](https://www.linkedin.com/in/guilhermeemiranda) | [GitHub](https://github.com/xguimiranda)

---

## ⚠️ Disclaimer

This project was developed for educational purposes as part of the Java OOP course by Prof. Dr. Nélio Alves. It runs entirely in the console and focuses on applying programming concepts rather than providing a full-featured commercial chess engine.
