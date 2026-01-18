# tron_python_light_cycle_game_web
python pygame webassembly html5 pygbag game-development tron ai

# 🟦 TRON: Light Cycles — WebAssembly Edition

A **browser-playable WebAssembly (HTML5)** adaptation of the Tron-inspired **Light Cycles** game, originally built with **Python + pygame**.

This version is modified to run directly in modern web browsers using **pygbag**, allowing the game to be played online without installing Python or pygame.  
The original desktop version lives in a separate repository.

---

## 🌐 Web Version Overview

- Runs fully in the browser via **WebAssembly**
- No downloads required for players
- Designed for embedding on platforms like itch.io and Systeme.io
- Same core gameplay and logic as the desktop version

---

## 🎮 Features

- ✅ Single Player vs AI
- ✅ Two Player local mode
- 🎯 Difficulty Selector (Easy / Normal / Hard)
- 🧠 AI opponent with survival + aggression logic
- 🟦 Neon glow light trails
- ⌨️ Keyboard controls
- 🌐 Browser-playable (HTML5 / WebAssembly)

---

## 🕹️ Controls

- **Arrow Keys** — Move Player 1
- **WASD** — Move Player 2 (two-player mode)
- Avoid walls, trails, and collisions to survive

---

## 🧪 Technical Details

- Language: **Python**
- Engine: **pygame**
- Web runtime: **WebAssembly (via pygbag)**
- Python version: **3.12+ recommended**
- Desktop build and Web build are maintained separately

---

## 🚀 Running the Web Version Locally

### 1️⃣ Create a build environment
```bash
python3 -m venv .venv-web
source .venv-web/bin/activate
pip install pygbag

- Python **3.12**
- pygame

### Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/your-repo-name.git
cd your-repo-name
