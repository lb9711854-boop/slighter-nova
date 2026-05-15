# slighter-nova
Apllication for game
<img width="503" height="576" alt="Screenshot 2026-05-15 154049" src="https://github.com/user-attachments/assets/50810bb9-7a34-4e2e-a95e-00b252352bd7" />
<img width="611" height="583" alt="Screenshot 2026-05-15 154039" src="https://github.com/user-attachments/assets/990cf848-19b9-4d8e-a6d6-ea4337a40a81" />
<img width="708" height="600" alt="Screenshot 2026-05-15 154030" src="https://github.com/user-attachments/assets/90e39b90-eccc-43cd-9ed1-a33bef2c61d1" />

# 🐍 Slither Nova Game

A colorful, smooth, neon-style snake game inspired by Slither.io.

---

# 🚀 Project Overview

Slither Nova is a browser-based snake game built using:
- JavaScript (Core game logic)
- Canvas API (Rendering engine)
- CSS (UI styling)
- HTML (structure)

---

# 🎮 Game Features

- Smooth snake movement
- Neon glowing snake effect
- Color-changing food system
- Score tracking system
- Level progression
- Increasing difficulty
- Mouse + touch control support
- Responsive fullscreen gameplay

---

# 🧠 How the Game Works

## Snake Movement
The snake follows the mouse position smoothly using interpolation for fluid motion.

## Food System
- Randomly generated food appears on the map
- Each food increases score and snake length

## Level System
- Every 50 points → level increases
- Higher levels increase difficulty and speed

## Collision System
- Eating food → grow snake
- Hitting food → score increase
- Self/wall collision → restart or game over (depending on version)

---

# 📁 Project Structure

```
slither-nova/
│
├── index.html   (UI + Canvas setup)
├── style.css    (Design & neon UI styling)
└── game.js      (Game logic engine)
```

---

# 🕹️ Controls

- 🖱️ Move Mouse → Control snake direction
- 📱 Touch Move → Mobile control support
- 🎯 Objective → Eat glowing orbs & grow

---

# ⚙️ Core Game Logic (Explanation)

## Snake Update Logic
- Snake head follows cursor
- Body follows previous positions
- Length increases when food is eaten

## Rendering Loop
- Uses `requestAnimationFrame`
- Continuously updates:
  - Snake
  - Food
  - Score
  - Background effects

---

# 🎨 Design Style

- Neon glow effects
- Dark space-like background
- HSL color cycling snake
- Particle-like glowing food

---

# 📊 Scoring System

| Action | Points |
|--------|--------|
| Eat food | +10 |
| Level up | Speed increases |
| Survival time | Higher score potential |

---

# 🚀 How to Run Locally

1. Download project files
2. Open `index.html` in browser
3. Start playing instantly

---

# 🌐 Deploy on GitHub Pages

1. Push repository to GitHub
2. Go to **Settings**
3. Open **Pages**
4. Select branch: `main`
5. Click Save
6. Game goes live 🎮

---

# 🔥 Future Enhancements

- Multiplayer online mode 🌍
- AI enemy snakes 🤖
- Skins and customization 🎨
- Power-ups ⚡
- Leaderboard system 🏆
- Mobile joystick control 📱
- Sound effects 🔊

---

# 🧩 Tech Stack

- JavaScript (ES6+)
- HTML5 Canvas API
- CSS3
- GitHub Pages (deployment)

---

# 🐍 End Note

Slither Nova is designed as a lightweight, fast, and expandable browser game that can be upgraded into a full multiplayer arcade experience.
## made with claude 
