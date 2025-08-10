# CSE423-project-Tank-Wars
Its is a 3D game created using openGL for my computer Graphics course.
Got it — I’ve read through your existing `README.md`, `3D_template.py`, and `base.py`.
I’ll now write you a **professional GitHub-style README** that expands on your current one, explaining the project in detail, including installation, features, controls, and gameplay mechanics.

---

# README.md (for GitHub)

````markdown
# 🚀 Tank Wars – CSE423 Project

**Tank Wars** is a 3D tank battle game built with **Python** and **OpenGL**, developed as part of the CSE423 Computer Graphics course.  
The game features **player-vs-AI combat**, realistic projectile physics, health bars, explosions, and obstacle-aware enemy AI.

---

## 🎮 Features

### Core Gameplay
- **Two tanks**:
  - Player (Blue)
  - AI Enemy (Red)
- **Health-based combat system** with floating health bars.
- **Projectile shooting** with collision detection and explosion effects.
- **Enemy AI** that intelligently chases or evades based on map obstacles.
- **Camera controls** for zoom and height adjustment.
- **3D OpenGL rendering** with smooth animations.

### Graphics & Rendering
- Built using **PyOpenGL**.
- Orthographic projection for HUD elements (text, health bars).
- Lighting and shading effects for a realistic environment.

---

## 🕹️ Controls

### Keyboard
| Key | Action |
|-----|--------|
| W   | Move forward |
| S   | Move backward |
| A   | Rotate left |
| D   | Rotate right |
| SPACE | Fire projectile |
| Q   | Zoom in |
| E   | Zoom out |
| R   | Increase camera height |
| F   | Decrease camera height |
| ESC | Quit game |

---

## 📦 Installation

### Prerequisites
Make sure you have Python **3.8+** installed and the following packages:

```bash
pip install PyOpenGL PyOpenGL_accelerate
````

---

## ▶️ Running the Game

Clone the repository and run:

```bash
git clone https://github.com/your-username/CSE423-project-Tank-Wars.git
cd CSE423-project-Tank-Wars
python base.py
```

---

## 🏗️ Project Structure

```
CSE423-project-Tank-Wars/
│── base.py              # Main game logic and event loop
│── 3D_template.py       # Camera setup and text rendering
│── README.md            # Project documentation
│── assets/              # (Optional) Game assets like textures, sounds
```

---

## 📚 Technical Details

* **Game loop**:

  * Uses GLUT’s idle function for continuous updates.
  * Manages tank movement, bullet physics, and collisions.
* **Rendering**:

  * Grid floor rendering.
  * Tanks and bullets drawn using OpenGL primitives.
* **AI Logic**:

  * Calculates distance and angle to player.
  * Avoids obstacles using simple steering behavior.

---

## 👨‍💻 Contributors

* *Your Name Here*

---

## 📜 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

```

---

If you want, I can also **add a “Game Description” section** at the top with a short engaging intro for GitHub visitors. That will make it even more attractive.
```
