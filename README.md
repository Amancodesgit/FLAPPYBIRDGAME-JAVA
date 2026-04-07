# 🐦 Flappy Bird – Java AWT/Swing

A classic Flappy Bird game built using Java's built-in AWT and Swing graphics libraries.
No external dependencies required!

---

## 🎮 Demo

![Flappy Bird Gameplay](assets/gameplay.gif)
<!-- Add a screen recording or screenshot here -->

---

## 🚀 Features

- 🎯 Smooth game loop using javax.swing.Timer
- 🖼️ Custom graphics drawn using JFrame and JPanel
- 🐦 Bird jumps on mouse click / spacebar press
- 🌿 Randomly generated pipes that move across the screen
- 💥 Collision detection between bird and pipes
- 🔢 Live running score display
- 🔄 Game over and restart logic

---

## 🛠️ Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)
![AWT](https://img.shields.io/badge/AWT-Swing-blue?style=flat)

| Technology | Usage |
|---|---|
| Java | Core programming language |
| AWT | Graphics rendering |
| Swing (JFrame/JPanel) | Window and panel management |
| javax.swing.Timer | Game loop |

---

## 📁 Project Structure
FlappyBird/
│
├── src/
│   ├── App.java           # Entry point – launches JFrame
│   ├── FlappyBird.java    # Main game panel (JPanel)
│   ├── Bird.java          # Bird object (position, velocity, jump)
│   └── Pipe.java          # Pipe object (position, random height)
│
├── assets/
│   ├── flappybird.png     # Bird image
│   ├── pipe.png           # Pipe image
│   └── background.png     # Background image
│
└── README.md
---

## ⚙️ How to Run

### Prerequisites
- Java JDK 8 or above installed
- Any IDE (IntelliJ IDEA / VS Code) or command line

### Steps

**Using Command Line:**
```bash
# Clone the repository
git clone https://github.com/Amancodesgit/FlappyBird.git

# Navigate to project
cd FlappyBird/src

# Compile
javac App.java

# Run
java App
```

**Using IntelliJ IDEA:**
1. Open the project folder
2. Right-click `App.java` → Run

---

## 🕹️ How to Play

| Action | Control |
|---|---|
| Make bird jump | `Mouse Click` or `Spacebar` |
| Restart after game over | `Mouse Click` |

- Avoid hitting the pipes
- Each pipe you pass = +1 score
- Game ends on collision with pipe or ground

---

## 📸 Screenshots

| Gameplay | Game Over |
|---|---|
| ![gameplay](assets/gameplay.png) | ![gameover](assets/gameover.png) |

---

## 🧠 What I Learned

- How to build a **game loop** using `javax.swing.Timer`
- Drawing images and shapes using **Graphics2D**
- Implementing **collision detection** with rectangle bounds
- Handling **keyboard and mouse events** in Swing
- **Random pipe generation** and smooth scrolling

---

## 🙋‍♂️ Author

**Aman Patel**
- 📧 amanpatel24oct@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/aman-174373270)
- 🐙 [GitHub](https://github.com/Amancodesgit)

---

## ⭐ If you like this project, give it a star!
