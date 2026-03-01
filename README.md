<h1 align="center">⚡ SudoSpark — Light Up Your Brain</h1>

<p align="center">
  <strong>A vibrant, modern Sudoku puzzle game that sparks joy while sharpening your mind.</strong>
</p>

<p align="center">
  <a href="https://prajitdatta.github.io/">🎮 Play Now</a> · 
  <a href="#features">✨ Features</a> · 
  <a href="#screenshots">📸 Screenshots</a> · 
  <a href="#tech-stack">🛠 Tech Stack</a> · 
  <a href="https://github.com/prajitdatta">👤 Author</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-FF6B35?style=flat-square" alt="Version">
  <img src="https://img.shields.io/badge/license-MIT-6C63FF?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/PRs-welcome-2ED573?style=flat-square" alt="PRs Welcome">
  <img src="https://img.shields.io/badge/made%20with-❤️-FF6B9D?style=flat-square" alt="Made with love">
</p>

---

## 🧩 What is SudoSpark?

**SudoSpark** is a beautifully crafted, browser-based Sudoku game designed to be fun, motivating, and visually delightful. No installs, no ads, no bloat — just pure puzzle joy with a spark.

Built as a single-page application with zero dependencies, it runs entirely in your browser and features a warm, vibrant UI that makes solving puzzles feel like a celebration.

---

## <a name="features"></a>✨ Features

| Feature | Description |
|---------|-------------|
| 🎨 **Vibrant UI** | Warm, light theme with playful colors, smooth animations, and micro-interactions |
| 🧠 **4 Difficulty Levels** | Easy, Medium, Hard, and Expert — puzzles are algorithmically generated |
| 📝 **Notes Mode** | Pencil in candidate numbers with a toggleable notes system |
| 💡 **Smart Hints** | 3 hints per game that reveal the correct number for a cell |
| 🔥 **Streak System** | Track consecutive correct answers — motivational toasts at milestones |
| ⭐ **Scoring Engine** | Dynamic scoring based on difficulty, speed, streak, and accuracy |
| ↩️ **Undo Support** | Full undo history for every action (place, erase, note) |
| ⏱️ **Live Timer** | Track your solve time with a clean, real-time timer |
| 💔 **Mistake Tracking** | 3 mistakes allowed — keeps you sharp and careful |
| 🎉 **Win Celebration** | Confetti animation and stats summary on puzzle completion |
| ⌨️ **Keyboard Support** | Full keyboard controls — arrow keys, number keys, and shortcuts |
| 📱 **Fully Responsive** | Plays perfectly on desktop, tablet, and mobile |
| 🚀 **Zero Dependencies** | Pure HTML/CSS/JS — no frameworks, no build step, instant load |

---

## <a name="screenshots"></a>📸 Preview

```
┌─────────────────────────────────────────────────┐
│                  ⚡ SudoSpark                     │
│              Light Up Your Brain ✨               │
│                                                   │
│   ☀️ Easy  🔥 Medium  💎 Hard  🧠 Expert         │
│                                                   │
│  ⏱️ 03:42    ┌───┬───┬───┐     [1] [2] [3]      │
│  🔥 Streak 7 │ 5 │   │ 3 │     [4] [5] [6]      │
│  💔 0/3      │   │ 8 │   │     [7] [8] [9]      │
│  ⭐ 540      │ 7 │   │ 1 │                       │
│              └───┴───┴───┘     📝 Notes          │
│                                🧹 Erase          │
│                                💡 Hint (3)       │
│                                ↩️ Undo            │
└─────────────────────────────────────────────────┘
```

---

## 🕹️ How to Play

1. **Select a cell** by clicking/tapping on it
2. **Enter a number** (1–9) using the number pad or keyboard
3. Fill every **row**, **column**, and **3×3 box** with numbers 1–9 without repeating
4. Use **Notes** mode to pencil in possible candidates
5. Use **Hints** when stuck (3 per game)
6. Avoid mistakes — you only get **3**!

### ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `1`–`9` | Place number |
| `Delete` / `Backspace` | Erase cell |
| `N` | Toggle notes mode |
| `H` | Use hint |
| `Z` | Undo |
| `Arrow keys` | Navigate cells |

---

## <a name="tech-stack"></a>🛠 Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, Grid, Flexbox, animations
- **Vanilla JavaScript** — ES6+ classes, no frameworks
- **Google Fonts** — Fredoka + Nunito typeface pairing
- **Algorithm** — Backtracking-based Sudoku generator with uniqueness validation


---

## 🎯 Scoring System

| Factor | Points |
|--------|--------|
| Correct placement | 10 × difficulty multiplier |
| Streak bonus | +2 points per 5-streak |
| Time bonus | (600 − seconds) × difficulty multiplier |
| **Difficulty multipliers** | Easy: 1×, Medium: 2×, Hard: 3×, Expert: 5× |

---

## 🧮 Puzzle Generation Algorithm

SudoSpark uses a custom Sudoku engine that:

1. **Generates** a complete valid board using randomized backtracking
2. **Removes** cells one at a time while checking for solution uniqueness
3. **Validates** each removal by attempting alternative solutions
4. **Guarantees** every puzzle has exactly one valid solution

Clue counts by difficulty: Easy (42), Medium (34), Hard (28), Expert (23).

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 👤 Author

**Prajit Datta**

- 🌐 Website: [prajitdatta.github.io](https://prajitdatta.github.io/)
- 🐙 GitHub: [@prajitdatta](https://github.com/prajitdatta)

---

<p align="center">
  Built with 💛 and ⚡ by <a href="https://github.com/prajitdatta">Prajit Datta</a>
</p>

<p align="center">
  <em>Every puzzle solved is a spark of brilliance. Keep playing, keep growing.</em> ⚡
</p>
