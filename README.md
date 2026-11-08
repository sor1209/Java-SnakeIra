<div align="center">

# 🐍 SnakeIra

**A classic Snake game built with Java Swing**

[![Java](https://img.shields.io/badge/Java-17-ED8B00?logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![Maven](https://img.shields.io/badge/Build-Maven-C71A36?logo=apachemaven&logoColor=white)](https://maven.apache.org/)

</div>

---

## About

SnakeIra is a desktop Snake game implemented in Java Swing. Guide the snake around the board, collect food, grow longer, and avoid collisions with the walls, your own body, and obstacles.

## Features

- Classic grid-based Snake gameplay
- Keyboard controls
- Score display
- Obstacles placed around the board
- Special food that increases the game speed
- Game-over screen with an Enter-to-restart flow
- Custom image assets for the snake, food, and obstacles

## Technology

- Java 17
- Java Swing and AWT
- Maven project configuration

## Project structure

```text
src/
├── images/                         # Game sprites and image assets
└── main/
    └── java/com/project/snakeira/
        ├── SnakeIra.java            # Application window and entry point
        ├── Board.java               # Game loop, rendering and controls
        └── Obstacles.java           # Obstacle layout and collision checks
pom.xml                              # Maven configuration
```

## Build

### Requirements

- JDK 17
- Apache Maven

Clone the repository:

```bash
git clone https://github.com/sor1209/Java-SnakeIra.git
cd Java-SnakeIra
```

Compile the project:

```bash
mvn clean package
```

You can also open the project in an IDE that supports Maven and run the main class:

```text
com.project.snakeira.SnakeIra
```

Keep the `src/images/` directory in the expected location because the game loads its sprites using relative file paths.

## Controls

| Key | Action |
|---|---|
| Arrow keys | Change the snake's direction |
| Enter | Restart after Game Over |

## Gameplay note

The board includes fixed obstacles. Plan turns carefully and avoid reversing directly into the snake's body.

---

<div align="center">

**SnakeIra · Java Desktop Game**

</div>
