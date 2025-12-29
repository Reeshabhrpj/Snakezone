# SnakeZone 🐍

A classic Snake game built with HTML, CSS, and JavaScript featuring smooth gameplay, sound effects, and high score tracking.

## 🎮 Features

- **Classic Snake Gameplay**: Navigate the snake to eat food and grow longer
- **Score System**: Real-time score tracking with persistent high score storage
- **Sound Effects**: Immersive audio including background music, food eating, movement, and game over sounds
- **Responsive Design**: Optimized for different screen sizes
- **Collision Detection**: Game ends when snake hits walls or itself
- **Local Storage**: High scores are saved locally in your browser

## 🚀 How to Play

1. Open `index.html` in your web browser
2. Use arrow keys to control the snake:
   - ⬆️ **Up Arrow**: Move up
   - ⬇️ **Down Arrow**: Move down
   - ⬅️ **Left Arrow**: Move left
   - ➡️ **Right Arrow**: Move right
3. Eat the food (colored squares) to grow and increase your score
4. Avoid hitting the walls or the snake's own body
5. Try to beat your high score!

## 🛠️ Technologies Used

- **HTML5**: Game structure and canvas
- **CSS3**: Styling, animations, and responsive design
- **JavaScript**: Game logic, collision detection, and score management
- **Web Audio API**: Sound effects and background music
- **Local Storage API**: High score persistence

## 📁 Project Structure

```
Snakezone/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Game styling
├── js/
│   └── first.js        # Game logic and functionality
├── favicon/            # Website icons
├── bg.jpg             # Background image
├── food.mp3           # Food eating sound
├── gameover.mp3       # Game over sound
├── move.mp3           # Movement sound
├── music.mp3          # Background music
└── README.md          # Project documentation
```

## 🎯 Game Mechanics

- **Grid System**: 18x18 game board
- **Speed**: Adjustable game speed (default: 7 FPS)
- **Food Generation**: Random food placement after consumption
- **Growth**: Snake grows by one segment per food eaten
- **Collision**: Game resets on wall or self-collision

## 🔧 Installation & Setup

1. Clone or download the repository
2. Navigate to the project directory
3. Open `index.html` in any modern web browser
4. No additional setup required!

## 🎵 Audio Features

- Background music plays continuously during gameplay
- Sound effects for:
  - Snake movement
  - Food consumption
  - Game over events

## 💾 High Score System

The game automatically saves your highest score using browser's local storage. Your high score persists between gaming sessions.

## 🌐 Browser Compatibility

Compatible with all modern web browsers that support:
- HTML5
- CSS3
- ES6 JavaScript
- Web Audio API
- Local Storage

## 📱 Responsive Design

The game adapts to different screen sizes using viewport units (vmin) for consistent gameplay across devices.

---

**Enjoy playing SnakeZone! 🎮**