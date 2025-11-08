
<div align="center">

![Pacman Banner](images/PackManBanner.png)

# 🟡 Pacman Game in Jack Language  
### 🕹️ Built for the Nand2Tetris Platform  

---

### 🎯 Overview  
This project is a **Pacman clone** developed entirely in the **Jack programming language** — part of the *Nand2Tetris* course.  
It demonstrates object-oriented design, graphics rendering, keyboard control, and game logic, all built on top of the Hack computer system.

<p align="center">
  <img src="images/PackMaN.gif" alt="Pacman Game" width="900">
</p>
---

### 📂 Project Structure  

| File | Description |
|------|--------------|
| **Main.jack** | Initializes and runs the game. |
| **Game.jack** | Controls the overall game flow, updates objects, and handles win/loss conditions. |
| **PacMan.jack** | Defines the Pacman character’s movement and behavior. |
| **Ghost.jack / Ghosts.jack** | Logic for ghost enemies — movement, AI, and collision detection. |
| **Pellet.jack / Pellets.jack** | Manages collectible dots and their interactions with Pacman. |
| **Wall.jack / Walls.jack** | Handles screen boundaries and obstacles. |
| **Score.jack** | Displays and updates the player’s score. |
| **Splash.jack** | Shows the start or game-over screens. |
| **Label.jack / Labels.jack** | Utility for displaying text labels on screen. |
| **Random.jack** | Random number generator for ghost behavior. |

---

### 🧠 Features  
- 🟡 Classic Pacman gameplay  
- 👻 Ghost enemies with basic AI  
- 🍒 Collectible pellets and scoring system  
- 💥 Collision and game-over detection  
- 🎨 Uses Nand2Tetris built-in `Screen` and `Keyboard` classes  
- 💻 Fully compatible with the **VM Emulator**  

---

### ⚙️ How to Run  [To run the game, you need to install VM Emulator on JVM]

- Install Java

- download the official [Nand2tetris Software Suite](https://www.nand2tetris.org/software)

- run VMEmulator.sh

- [File] -> [Load Program] -> select source/Tetris of this repository -> press [Load Program]

- When confirmation message pops up, press Yes (for better game speed, master brand relies on the build-in OS

- Hit Enter key to start.

- Now you are ready to go!

- To resume after gameover, hit [F2] or [fn+F2].

