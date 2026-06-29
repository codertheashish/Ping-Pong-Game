# 🏓 Ping Pong – Color & Score Sync (Python + Pygame)

### Smooth Gameplay • Color-Changing Ball • Synced Score • AI Opponent

A fully polished **Ping Pong game** built using **Python Pygame**, featuring synchronized **ball color + score color**, smooth paddle mechanics, AI opponent tracking, speed-increasing ball physics, and a clean, minimal UI.

The ball changes color **every time the player hits it**, and the score instantly syncs to match the ball color. The game ends at 7 points with a dedicated **Game Over screen** including Restart & Exit options.

---

## 🚀 Game Features

### 🎨 Color-Sync System

* Ball changes color on every **player paddle return**
* Score color changes **together with the ball**
* Colors cycle through:

  * White → Green → Yellow → Orange → Red → Purple

### 🏓 Smooth Controls

* Player paddle moves up/down
* Simple arrow-key control
* Smooth movement without jitter

### 🤖 Smart AI Opponent

* AI paddle automatically tracks the ball
* Slower movement so the player has advantage

### ⚡ Progressive Difficulty

* Ball speed **gradually increases** after every paddle hit
* Game becomes harder but stays smooth

### 🔥 Game Over Screen

* Clean UI
* Shows “GAME OVER”
* Options available:

  * **R** → Restart
  * **ESC** → Quit game

### 🧮 Score System

* First to **7 points** wins
* Score appears at the top center
* Color dynamically synced with ball

---

## 🎮 Controls

| Key | Action                  |
| --- | ----------------------- |
| ↑   | Move paddle up          |
| ↓   | Move paddle down        |
| R   | Restart after Game Over |
| ESC | Quit game               |

---

## 🛠 Tech Stack

* **Python 3.x**
* **Pygame**
* Random module for ball direction

---

## 📦 Installation

### **1️⃣ Install Python (if not installed)**

### **2️⃣ Install Pygame**

```bash
pip install pygame
```

### **3️⃣ Clone the Repository**

```bash
https://github.com/codertheashish/Ping_pong_game.git
```

### **4️⃣ Run the Game**

```bash
python ping_pong_game.py
```

---

## ▶ How the Game Works

* Ball starts in the center and moves automatically
* Player hits the ball using arrow keys
* Each hit:

  * Increases ball speed slightly
  * Changes ball color
  * Score color updates instantly
* AI paddle follows the ball with reduced speed
* If ball crosses a side:

  * Corresponding player gets a point
  * Ball resets to center
* Game ends when:

  * **Player score = 7**
  * OR **AI score = 7**

---

## 📁 Output / Visuals

The game includes:

* Black background
* Blue (player) and Red (AI) paddles
* Multicolor dynamic ball
* Matching color score
* Smooth 60 FPS motion
* Professional Game Over screen

---

## 🌟 Future Improvements

* Add sound effects
* Add trails for the ball
* Add difficulty modes
* Add high score save system
* Add two-player local mode

---

## 👨‍💻 Author

**Ashish Kumar Prajapati**

---

<img width="1672" height="941" alt="Ping_pong_game" src="https://github.com/user-attachments/assets/0f614feb-d4bb-4f65-bfa5-0dd2ba5378b0" />
