# simplegalaga.github.io
simple ver of galaga
# 🚀 Simple Galaga

A classic arcade-style space shooter game built with p5.js, inspired by the legendary Galaga arcade game. Battle against waves of alien invaders in this retro-styled web game!

## 🎮 Play Now

[**Play the Game**](https://yourusername.github.io/simple-galaga) *(Replace with your actual GitHub Pages URL)*

## 🎯 Game Features

- **Classic Arcade Gameplay**: Move, shoot, and survive waves of enemies
- **Responsive Controls**: Smooth movement with keyboard controls
- **Enemy AI**: Aliens move in formation and shoot back at you
- **Progressive Difficulty**: Continuous enemy waves with varying spawn patterns
- **Score System**: Earn points by destroying enemies
- **Lives System**: Start with 3 lives - avoid enemy fire and collisions
- **Retro Aesthetics**: Green and cyan color scheme with glowing effects
- **Animated Background**: Scrolling starfield for immersion

## 🕹️ Controls

| Key | Action |
|-----|--------|
| ← → | Move ship left/right |
| Spacebar | Shoot bullets |
| R | Restart game (when game over) |

## 🎪 Screenshots

```
    🚀 SIMPLE GALAGA 🚀
Use ARROW KEYS to move • SPACEBAR to shoot

┌─────────────────────────────────────┐
│  👾   👾   👾   👾   👾   👾   👾   │
│    👾   👾   👾   👾   👾   👾     │
│  👾   👾   👾   👾   👾   👾   👾   │
│                                     │
│              ⚡ ⚡ ⚡                │
│                                     │
│                 ▲                   │
│                🔥                   │
└─────────────────────────────────────┘
Score: 2100 | Lives: 2
```

## 🛠️ Technical Details

### Built With
- **p5.js** - Creative coding library for graphics and interaction
- **HTML5 Canvas** - For smooth 2D rendering
- **Vanilla JavaScript** - Game logic and mechanics
- **CSS3** - Styling and visual effects

### Game Architecture
- **Object-Oriented Design**: Separate classes for Player, Enemy, and Bullet objects
- **Collision Detection**: Precise bounding box collision system
- **Game State Management**: Playing and Game Over states
- **Dynamic Spawning**: Intelligent enemy wave and individual spawn system

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)
1. Fork this repository
2. Go to Settings → Pages
3. Set source to "Deploy from a branch" → `main`
4. Your game will be live at `https://yourusername.github.io/simple-galaga`

### Option 2: Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/simple-galaga.git
   cd simple-galaga
   ```

2. Open `index.html` in your web browser, or serve it locally:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

## 📁 Project Structure

```
simple-galaga/
├── index.html          # Main game file with HTML, CSS, and JavaScript
├── README.md          # This file
└── LICENSE            # MIT License (optional)
```

## 🎮 Gameplay Tips

- **Movement Strategy**: Stay mobile! Don't stay in one place too long
- **Shooting Timing**: Rapid-fire by holding spacebar, but be strategic
- **Enemy Patterns**: Watch for enemy movement patterns to predict their shots
- **Wave Survival**: Clear enemies quickly to prevent overwhelming numbers
- **Score Maximization**: Each enemy is worth 100 points - go for high scores!

## 🔧 Customization

The game is highly customizable! You can easily modify:

- **Game Speed**: Adjust `player.speed` and enemy movement speeds
- **Difficulty**: Change `enemySpawnDelay` and enemy shooting frequency
- **Visual Style**: Modify colors, sizes, and effects in the drawing functions
- **Scoring**: Adjust point values in the collision detection
- **Lives**: Change starting lives count

Example customizations:
```javascript
// Make the game harder
let enemySpawnDelay = 1000; // Spawn enemies faster
let lives = 1; // Start with only 1 life

// Change colors for different theme
fill(255, 0, 255); // Magenta player ship
```

## 🤝 Contributing

Contributions are welcome! Here are some ideas for improvements:

- **Power-ups**: Add weapon upgrades, shields, or speed boosts
- **Sound Effects**: Integrate Web Audio API for shooting and explosion sounds
- **Boss Battles**: Create larger, more challenging enemy types
- **High Score System**: Implement local storage for score persistence
- **Mobile Support**: Add touch controls for mobile devices
- **Particle Effects**: Enhanced visual effects for explosions

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Inspired by the classic **Galaga** arcade game by Namco
- Built with [p5.js](https://p5js.org/) - a wonderful creative coding library
- Thanks to the retro gaming community for keeping classic arcade games alive

## 📞 Contact

- **Your Name** - [@yourtwitter](https://twitter.com/yourtwitter)
- **Project Link**: [https://github.com/yourusername/simple-galaga](https://github.com/yourusername/simple-galaga)

---

### 🌟 Star this repository if you enjoyed the game!

*Made with ❤️ and JavaScript*
