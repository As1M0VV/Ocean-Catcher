# 🌊 Ocean Catcher

A 2D web-based survival and collecting game built with **HTML5 Canvas**, **JavaScript**, and **CSS3**.  
Developed as a Computer Graphics course project at Istanbul Arel University.

---

## 🎮 Gameplay

Take control of a deep-sea diver and collect valuable treasures falling from above — but watch out for dangers lurking in the ocean!

- Move your diver with **← →** arrow keys (or touch/drag on mobile)
- Catch valuable items to earn points
- Avoid jellyfish and trash or you'll lose a life
- Every **100 points** you level up — the game gets faster and harder!
- You start with **3 lives ❤️❤️❤️** — lose them all and it's game over

---

## 🐠 Items

| Item | Name | Points |
|------|------|--------|
| 🐟 | Fish | +10 pts |
| ⭐ | Starfish | +25 pts |
| 💎 | Crystal | +50 pts |
| 🎁 | Bonus Box | +100 pts |
| 🪼 | Jellyfish | **DANGER** (−1 life) |
| 🗑️ | Trash | **DANGER** (−1 life) |

---

## ✨ Features

- **Dynamic difficulty** — spawn rate and object speed increase with each level
- **Particle effects** — visual feedback on every catch or collision
- **Score popups** — floating +pts / -❤️ indicators
- **High score tracking** — best score saved via `localStorage`
- **Diver tilt animation** — diver leans left/right while moving
- **Animated ocean background** — bubbles, seaweed, light rays
- **Touch support** — playable on mobile devices
- **Weighted random spawning** — rarer items appear less frequently

---

## 🛠️ Tech Stack

- **HTML5 Canvas API** — game rendering & 2D transformations (`ctx.translate`, `ctx.rotate`)
- **Vanilla JavaScript** — game loop via `requestAnimationFrame`, collision detection, particle system
- **CSS3** — UI overlay, glassmorphism stat boxes, animations
- **Google Fonts** — Fredoka One, Nunito

---

## 🚀 How to Run

No installation needed. Just open `index.html` in your browser:

```bash
git clone https://github.com/As1M0VV/Ocean-Catcher.git
cd Ocean-Catcher
# Open index.html in your browser
```

Or simply double-click `index.html`.

---

## 📁 Project Structure

```
Ocean-Catcher/
├── index.html   # Game structure & UI
├── script.js    # Game logic, rendering, input handling
└── style.css    # Styling & animations
```

---

## 👨‍💻 Author

**Asım Seyran** — Computer Engineering Student, Istanbul Arel University  
[GitHub](https://github.com/As1M0VV) · [LinkedIn](https://www.linkedin.com/in/asım-seyran-216491355/)
