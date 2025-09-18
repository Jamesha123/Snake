# Snake Game

A classic Snake game implementation using Java Swing framework.

## 🎮 Game Description

This is a traditional Snake game where you control a snake that moves around the screen, eating apples to grow longer and increase your score. The game ends when the snake hits the walls or itself.

## 🚀 Features

- **Smooth gameplay** with 70ms delay between moves
- **Responsive controls** using arrow keys or WASD
- **Score tracking** displayed in real-time
- **Game over screen** with final score
- **Grid-based movement** for precise control
- **Random apple placement** for varied gameplay

## 🎯 How to Play

### Controls
- **Arrow Keys** or **WASD** to move the snake
- **Up/W** - Move up
- **Down/S** - Move down  
- **Left/A** - Move left
- **Right/D** - Move right

### Objective
- Guide the snake to eat red apples
- Each apple increases your score and makes the snake longer
- Avoid hitting the walls or your own body
- Try to achieve the highest score possible!

## 🛠️ Technical Details

### Requirements
- Java 8 or higher
- Java Runtime Environment (JRE)

### Project Structure
```
Snake/
├── src/
│   ├── SnakeGame.java    # Main class with entry point
│   ├── GameFrame.java    # JFrame window setup
│   └── GamePanel.java    # Game logic and graphics
├── bin/                  # Compiled class files
└── SnakeGame.jar         # Executable JAR file
```

### Game Specifications
- **Screen Size:** 600x600 pixels
- **Unit Size:** 25x25 pixels
- **Game Speed:** 70ms delay between moves
- **Initial Snake Length:** 6 segments

## 🏃‍♂️ Running the Game

### Option 1: Executable JAR (Recommended)
1. Double-click `SnakeGame.jar`
2. The game window will open automatically

### Option 2: Command Line
```bash
java -jar SnakeGame.jar
```

### Option 3: From Source Code
```bash
# Compile the source files
javac -d bin src/*.java

# Run the game
java -cp bin SnakeGame
```

## 🎨 Game Screenshots

The game features:
- Black background with white grid lines
- Pink snake with distinct head
- Red apples for food
- Real-time score display
- Game over screen with final score

## 🔧 Development

### Building from Source
1. Clone or download the project
2. Navigate to the project directory
3. Compile: `javac -d bin src/*.java`
4. Run: `java -cp bin SnakeGame`

### Creating Executable JAR
```bash
# Create manifest file
echo Manifest-Version: 1.0 > MANIFEST.MF
echo Main-Class: SnakeGame >> MANIFEST.MF

# Create JAR file
jar cfm SnakeGame.jar MANIFEST.MF -C bin .
```

**Enjoy playing Snake!** 🐍🍎
