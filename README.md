# ♟️ Chess Move Validator

A Unity-based **Chess Move Validator** that calculates and displays all valid moves for a chess piece based on its current position on a chess board.

The project allows you to configure the position of each chess piece and then interact with the board to visualize the moves available to that piece.

---

## 🎯 Features

* ♟️ Supports multiple chess pieces
* 🧩 Configure piece positions using **Unity Scriptable Objects**
* 📍 Set the **X and Y coordinates** of each piece
* 🏁 Automatically arranges pieces on the board when the game starts
* 🖱️ Click on a chess piece to display its valid moves
* 🔍 Visual representation of possible moves
* 🧠 Move validation based on the selected piece and board position
* 🎮 Built with Unity and C#

---

## 🖥️ How It Works

The project uses Scriptable Objects to store the position of each chess piece.

Each available piece has configurable **X** and **Y** position fields. These values determine where the piece will be placed on the chess board.

### Basic workflow

```text
Configure Piece Positions
          ↓
      Run Project
          ↓
Pieces Arrange Themselves
          ↓
    Click a Piece
          ↓
Valid Moves Are Displayed
```

---

## ⚙️ Project Setup

The Unity project files have been compressed and include the required:

* 📁 Assets
* 📦 Packages
* ⚙️ Project Settings

### 1. Extract the Project

Extract the compressed project files to a location of your choice.

Make sure the extracted project retains the Unity project structure, including folders such as:

```text
Assets/
Packages/
ProjectSettings/
```

### 2. Open with Unity Hub

Open **Unity Hub** and select:

**Add → Add project from disk**

Navigate to the extracted project folder and select it.

### 3. Select a Unity Editor Version

Open the project using your preferred compatible Unity Editor version.

> 💡 If Unity prompts you to upgrade or change the project version, make sure you have a backup of the project before proceeding.

### 4. Run the Project

Once the project is open:

1. Open the relevant scene.
2. Configure the positions of the chess pieces through their Scriptable Objects.
3. Set the desired **X** and **Y** coordinates.
4. Press ▶️ **Play**.
5. The pieces will automatically arrange themselves according to the configured positions.
6. Click on a chess piece to view its valid moves.

---

## 📍 Configuring Piece Positions

The position of each chess piece can be configured through its associated **Scriptable Object**.

Each piece provides:

```text
X → Horizontal board position
Y → Vertical board position
```

For example:

```text
X = 3
Y = 4
```

will place the corresponding piece at the board position represented by those coordinates.

This makes it easy to test different chess positions without manually moving the pieces in the Unity Editor.

---

## 🕹️ Using the Move Validator

After starting the project:

### 1. Select a Piece ♟️

Click on any available chess piece on the board.

### 2. View Valid Moves 🟩

The project calculates the legal movement options for the selected piece and displays them on the board.

### 3. Test Different Positions 🔄

Change the X/Y coordinates in the Scriptable Objects, restart the scene, and experiment with different board configurations.

This can be useful for testing movement logic across a variety of chess positions.

---

## 🧩 Project Structure

The project follows a standard Unity project structure:

```text
ChessMoveValidator/
│
├── Assets/
│   ├── Scripts/
│   ├── Scenes/
│   ├── ScriptableObjects/
│   ├── Prefabs/
│   └── ...
│
├── Packages/
│
└── ProjectSettings/
```

> 📌 The exact contents of the `Assets` folder may vary depending on the current version of the project.

---

## 🛠️ Technologies Used

* 🎮 **Unity**
* 💻 **C#**
* 🧱 **Unity Scriptable Objects**
* ♟️ Chess movement and validation logic

---

## 🚀 Purpose of the Project

This project was created to explore and demonstrate:

* Object-oriented programming in C#
* Chess piece movement logic
* Board coordinate systems
* Unity component-based architecture
* Scriptable Objects for configurable game data
* User interaction and input handling
* Algorithmic validation of possible moves

---

## 🔮 Possible Future Improvements

Some potential additions to the project include:

* 👑 Full chess rule validation
* ♟️ Pawn movement and promotion
* 🏰 Castling
* ⚔️ En passant
* 👑 Check and checkmate detection
* 🤖 Chess AI opponent
* 🎨 Improved move highlighting
* 🖱️ Drag-and-drop piece movement
* 🏆 Complete playable chess game
* 📋 FEN position import for quickly testing real chess positions

---

## 👨‍💻 Author

Developed as a Unity/C# project to explore **chess movement algorithms, game logic, and Unity architecture**.

⭐ If you find the project interesting, feel free to explore the code and experiment with different chess positions!
