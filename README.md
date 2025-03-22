# CollectandDodge

A fast-paced browser-based arcade game where players collect coins while dodging obstacles to reach level 50 and win the game.

![Collect and Dodge Game](screenshot.png)

## How to Play

1. Open `index.html` in any modern web browser to start the game
2. Use **arrow keys** or **WASD** to move your character
3. Collect colored coins to earn points:
   - Yellow coins: 10 points
   - Purple coins: 25 points
   - Teal coins: 50 points
4. Avoid the red square obstacles
5. Grab blue diamond-shaped shield power-ups for temporary protection
6. Try to reach level 50 to win the game!

## Game Features

### Progression System
- **50 Levels**: Progress through increasingly difficult levels
- **Progressive Difficulty**: Game gets harder as you level up with:
  - Faster and bigger obstacles
  - Spinning obstacles at higher levels
  - Screen shake effects
  - Visual color changes
  - More chaotic obstacle movement

### Scoring System
- **Combo System**: Chain multiple collectibles in a row to build up combos
- **Score Multiplier**: Earn up to 3x points with higher combos
- **High Score Tracking**: Your highest score is saved locally

### Visual Effects
- **Animated Starry Background**: Beautiful backdrop with twinkling stars
- **Particle Effects**: Collectibles burst into particles when collected
- **Shield Effects**: Temporary protection with visual feedback
- **Screen Effects**: Shake and color changes at higher difficulty levels
- **Level-up Animations**: Visual confirmation when advancing to the next level
- **Win Celebration**: Colorful confetti animation when you beat the game

### Power-ups
- **Shield Power-up**: Temporary invincibility that blocks one hit
- **Obstacle Explosion**: Obstacles explode when blocked by a shield

### Collectible Types
- **Common (Yellow)**: Worth 10 points, most frequent
- **Rare (Purple)**: Worth 25 points, medium rarity
- **Special (Teal)**: Worth 50 points, least common
- Collectible rarity adjusts with difficulty level

## Game Interface
- Clean, modern UI with gradient effects
- Difficulty meter shows your current challenge level
- Game header displays score, level, and remaining time
- Combo and multiplier indicators show your current streak
- Informative start screen, game over screen, and win screen

## Development

This game is built using vanilla HTML, CSS, and JavaScript. No external libraries or frameworks are required.

### File Structure
- `index.html`: Contains all game code (HTML, CSS, and JavaScript)
- `README.md`: This documentation file

### Technical Features
- Responsive collision detection
- Difficulty scaling algorithm
- Particle system for visual effects
- Local storage for persistent high scores
- Configurable game parameters via the CONFIG object

## Browser Compatibility

The game works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Credits

Developed by Micah Clark

## License

[MIT License](LICENSE) 
