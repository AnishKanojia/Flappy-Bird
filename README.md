# Flappy Bird Game in Python

This is a simple **Flappy Bird** game implemented using **Python** and **Pygame**. The game is a clone of the popular Flappy Bird game, where the player controls a bird and tries to navigate through obstacles to achieve the highest score.

---

## 🎮 Features
- Smooth gameplay using Pygame
- Realistic bird physics with gravity
- Sound effects for jumping, scoring, and collisions
- Randomly generated pipes for continuous gameplay

---

## 📂 Folder Structure
```
FlappyBird/
│-- gallery/
│   ├── sprites/
│   │   ├── bird.png
│   │   ├── background.png
│   │   ├── base.png
│   │   ├── pipe.png
│   │   ├── message.png
│   │   ├── 0.png, 1.png, 2.png, ... 9.png (Numbers for score display)
│   ├── audio/
│   │   ├── die.wav
│   │   ├── hit.wav
│   │   ├── point.wav
│   │   ├── swoosh.wav
│   │   ├── wing.wav
│-- flappy_bird.py  # Main game script
│-- README.md       # Project Documentation
```

---

## 🔧 Installation & Setup
### Prerequisites
Make sure you have **Python** installed on your system.

### Install Pygame
Run the following command to install the required library:
```bash
pip install pygame
```

---

## 🚀 How to Run the Game
1. **Download the project** or clone the repository:
   ```bash
   git clone https://github.com/AnishKanojia/FlappyBird.git
   cd FlappyBird
   ```
2. **Run the game** using Python:
   ```bash
   python flappy_bird.py
   ```

---

## 🎮 How to Play
- **Press SPACE or UP arrow** to make the bird jump.
- **Avoid hitting the pipes** or the ground.
- **Score points** by successfully passing through pipes.
- **Press ESC** to quit the game.

---

## 🛠 Customization
- Change the **player sprite** by modifying `gallery/sprites/bird.png`
- Change the **background image** by replacing `gallery/sprites/background.png`
- Modify the **pipe movement speed** in `flappy_bird.py` (variable: `pipeVelX`)

---

## 📜 License
This project is for educational purposes. Feel free to modify and improve it! 😊

---

## 👨‍💻 Author
Developed by **Anish Kanojia** 🚀

---

## 📢 Contributions
If you'd like to improve the game, feel free to submit a **pull request**! 🎉
