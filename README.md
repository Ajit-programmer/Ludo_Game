<div align="center">

<!-- Animated Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFD700,50:FF6B35,100:E63946&height=200&section=header&text=🎲%20Ludo%20Game%20AI&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Classic%20Ludo%20Reimagined%20with%20Artificial%20Intelligence&descAlignY=60&descSize=18" width="100%"/>

<!-- Badges Row 1 -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tkinter-GUI-FF6B35?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pillow-Imaging-4CAF50?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Stable-27AE60?style=for-the-badge"/>
</p>

<!-- Badges Row 2 -->
<p align="center">
  <img src="https://img.shields.io/badge/Game-Ludo-FFD700?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Mode-AI%20%7C%20Multiplayer-E63946?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Platform-Desktop-8E44AD?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Players-1--4-FF6B35?style=for-the-badge"/>
</p>

<br/>

> **🎮 A full-featured Ludo board game built with Python & Tkinter — play solo against an intelligent AI opponent or challenge up to 3 friends in a local multiplayer match!**

<br/>

<!-- Quick Links -->
<p>
  <a href="#-features">✨ Features</a> &nbsp;•&nbsp;
  <a href="#%EF%B8%8F-installation">⚙️ Installation</a> &nbsp;•&nbsp;
  <a href="#-how-to-play">🎮 How to Play</a> &nbsp;•&nbsp;
  <a href="#-game-modes">🕹️ Game Modes</a> &nbsp;•&nbsp;
  <a href="#-contributing">🤝 Contributing</a>
</p>

</div>

---

## 📸 Preview

<div align="center">
<table>
  <tr>
    <td align="center"><b>🏠 Entry Screen</b></td>
    <td align="center"><b>🎲 Gameplay</b></td>
  </tr>
  <tr>
    <td><img src="Documents/entry.png" alt="Entry Screen" width="350"/></td>
    <td><img src="Documents/ludo_ai_gif.gif" alt="Gameplay GIF" width="350"/></td>
  </tr>
</table>
</div>

---

## ✨ Features

<div align="center">

| Feature | Description |
|:---:|:---|
| 🤖 **AI Opponent** | Face off against a smart computer player with strategic move logic |
| 👥 **Multiplayer** | Play with 2 to 4 friends locally on the same machine |
| 🎨 **Visual GUI** | Clean, interactive board built with Python Tkinter + Pillow |
| 🎯 **Full Ludo Rules** | Authentic gameplay — home column, safe squares, token capture & home entry |
| 🎲 **Dice Mechanics** | Animated dice with proper roll-and-move logic |
| 🏆 **Win Detection** | Automatic winner announcement when all tokens reach home |
| 🔄 **Game Restart** | Reset and start a new game at any point |

</div>

---

## 🕹️ Game Modes

<div align="center">

```
┌─────────────────────────────────────────────────────────────────┐
│                       SELECT YOUR MODE                          │
├──────────────────────────┬──────────────────────────────────────┤
│   🤖  vs AI              │   👥  vs Friends                     │
│                          │                                      │
│  YOU  → 💙 Sky-Blue      │  2 – 4 Players                      │
│  CPU  → ❤️  Red           │  Each player gets a unique colour   │
│                          │                                      │
│  Perfect for solo play!  │  Gather the squad and battle it out!│
└──────────────────────────┴──────────────────────────────────────┘
```

</div>

### 🤖 Play vs AI
The computer controls the **Red** tokens and makes strategic decisions automatically. You control **Sky-Blue** tokens. It's a battle of luck and skill — can you beat the machine?

### 👥 Play vs Friends (Local Multiplayer)
Choose between **2, 3, or 4** human players. Each player takes their turn in sequence. Perfect for family game nights!

---

## ⚙️ Installation

### Prerequisites

Make sure you have the following installed on your system:

- **Python** `>= 3.3` — [Download Python](https://www.python.org/downloads/)
- **pip** — comes bundled with Python 3.4+

### Step 1 — Clone the Repository

```bash
git clone https://github.com/Ajit-programmer/Ludo_Game.git
cd Ludo_Game
```

### Step 2 — Install Dependencies

```bash
pip install pillow
```

> **Note for Python 3.11+ users:** If you encounter permission issues, use:
> ```bash
> pip install pillow --break-system-packages
> ```

### Step 3 — Run the Game 🚀

```bash
python Ludo_game.py
```

That's it! The game window will launch immediately. 🎉

---

## 🎮 How to Play

```
1. Launch the game using: python Ludo_game.py
2. Select your preferred game mode (vs AI or vs Friends)
3. Choose the number of players (if playing vs Friends)
4. Take turns rolling the dice
5. Move your tokens strategically around the board
6. Capture opponent tokens to send them back to start
7. First player to get all 4 tokens HOME wins! 🏆
```

### 📜 Game Rules at a Glance

- Roll a **6** to bring a token out of the starting area
- Safe squares protect your token from capture
- Landing on an opponent's token sends it back to start
- Navigate through the coloured home column to reach the centre
- All 4 tokens must enter the home square **exactly** (no overshoot)

---

## 🗂️ Project Structure

```
Ludo_Game/
│
├── 📄 Ludo_game.py          # Main game source code
├── 📄 Ludo_game.txt         # Game notes / documentation
├── 📁 Images/               # Game assets (board, tokens, dice)
├── 📄 README.md             # Project documentation
├── 📄 CONTRIBUTING.md       # Contribution guidelines
└── 📄 CODE_OF_CONDUCT.md    # Community standards
```

---

## 🛠️ Tech Stack

<div align="center">

| Technology | Purpose |
|:---:|:---|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Core game logic & AI |
| ![Tkinter](https://img.shields.io/badge/Tkinter-FF6B35?style=flat-square&logo=python&logoColor=white) | GUI framework & board rendering |
| ![Pillow](https://img.shields.io/badge/Pillow-4CAF50?style=flat-square&logo=python&logoColor=white) | Image processing for game assets |

</div>

---

## 🤝 Contributing

Contributions are warmly welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a new branch: `git checkout -b feature/your-feature-name`
3. **Commit** your changes: `git commit -m "Add: your feature description"`
4. **Push** to your branch: `git push origin feature/your-feature-name`
5. **Open** a Pull Request

> 📋 Before contributing, please read the [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) files.

---

## 📋 Roadmap

- [ ] 🌐 Online multiplayer support
- [ ] 🔊 Sound effects & background music
- [ ] 🎨 Multiple board themes / skins
- [ ] 📊 Score tracking & leaderboard
- [ ] 🤖 Multiple AI difficulty levels (Easy / Medium / Hard)
- [ ] 📱 Mobile-responsive version

---

## 📄 License

This project is open source. Feel free to use, modify, and distribute it. See the repository for full license details.

---

<div align="center">

### ⭐ If you enjoyed this project, consider giving it a star!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFD700,50:FF6B35,100:E63946&height=120&section=footer" width="100%"/>

**Made with ❤️ by [Ajit-programmer](https://github.com/Ajit-programmer)**

</div>
