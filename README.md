# 🪢 Hangman Game

> 🎮 A classic word-guessing game built in **Java**, designed with clean OOP architecture — abstraction, interfaces, and separation of concerns.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apachemaven&logoColor=white)
![OOP](https://img.shields.io/badge/OOP-Design-blueviolet?style=flat)

## 📌 Overview

**Hangman** is the timeless word-guessing game: the player tries to find the hidden word letter by letter, with a limited number of wrong guesses before the game is over. 💀

Beyond the game itself, this project focuses on **writing clean, well-structured Java code** using core object-oriented principles.

## ✨ Features

- 🔤 Letter-by-letter word guessing with input validation
- ❤️ Limited attempts — lose a life on every wrong guess
- 🎯 Win/lose detection with clear game states
- 🔄 Replayable game loop

## 🏗️ Architecture & OOP Concepts

The project follows a layered design that separates game logic from control flow:

| File | Role |
|---|---|
| `AbstractHangmanGame.java` | 🧩 Abstract base class — shared game behavior |
| `HangmanGame.java` | 📐 Game contract (interface) |
| `HangmanGameImpl.java` | ⚙️ Concrete game logic implementation |
| `HangmanController.java` | 🎮 Controls game flow & user interaction |
| `Main.java` | 🚀 Application entry point |

**Concepts applied:** abstraction · inheritance · interfaces · encapsulation · separation of concerns

## 💻 Tech Stack

- ☕ Java
- 📦 Maven (build & dependency management)

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/hangman-game.git
cd hangman-game

# Build and run with Maven
./mvnw clean compile exec:java
```

Or simply open the project in your IDE (IntelliJ / VS Code) and run `Main.java`. ▶️
