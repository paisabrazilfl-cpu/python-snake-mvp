# 🐍 Python Snake MVP

A complete, runnable **Snake game** built with **pygame** — featuring bold, cartoonish 2D graphics inspired by the vibrant worlds of **Street Fighter** and **Super Mario**.

---

## 🎮 Gameplay

- Classic snake mechanics: eat food, grow longer, avoid walls and yourself.
- Score tracking displayed live on screen.
- Increasing difficulty as the snake grows.
- Smooth 60 FPS game loop with keyboard controls (arrow keys / WASD).

## 🎨 Visual Style

The graphics are drawn entirely with pygame primitives (rectangles, circles, polygons) — no external image assets needed:

- **Mario-inspired**: bright sky-blue background, green "grass" border, cartoonish food items (cherry/apple shapes), playful rounded aesthetic.
- **Street Fighter-inspired**: bold color palette — fiery reds, electric blues, golden yellows, deep shadows; the snake segments have a "combo meter" gradient that intensifies as you score higher; KO-style game-over screen with dramatic text.

## 🚀 Installation

```bash
# Clone the repo
git clone https://github.com/paisabrazilfl-cpu/python-snake-mvp.git
cd python-snake-mvp

# Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## 🕹️ Run

```bash
python main.py
```

- Use **Arrow Keys** or **WASD** to steer the snake.
- Press **P** to pause/resume.
- Press **R** to restart after game over.
- Press **ESC** or close the window to quit.

---

## 📁 Project Structure

```
python-snake-mvp/
├── README.md           # This file
├── requirements.txt    # Python dependencies
├── main.py             # The complete game (single-file, runnable)
└── assets/             # Placeholder folder (no external assets required)
```

## 🔧 Requirements

- Python 3.8+
- pygame >= 2.0

---

*Built as an MVP — pure pygame, zero external assets, maximum style.*