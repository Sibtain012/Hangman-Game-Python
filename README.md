# HANGMAN-GAME-PYTHON

*Guess, Engage, Win: Unleash Your Word Power!*

![Last Commit](https://img.shields.io/badge/last%20commit-today-brightgreen)
![Python](https://img.shields.io/badge/python-100%25-blue)
![Languages](https://img.shields.io/badge/languages-1-blue)

---

_Built with the tools and technologies:_

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)

---

## 📚 Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Testing](#testing)
- [Features](#features)
- [Project Structure](#project-structure)
- [Game Flow](#game-flow)
- [License](#license)

---

## 📝 Overview

Hangman-Game-Python is an engaging implementation of the classic Hangman game, designed to provide players with an interactive and educational experience as they guess letters to reveal hidden words.

### Why Hangman-Game-Python?

This project enhances the traditional Hangman gameplay by incorporating visual elements and a diverse vocabulary. The core features include:

🎮 **Interactive Gameplay**: Engage users with a fun and challenging word-guessing experience.

📚 **Diverse Word Repository**: Access a comprehensive list of words to keep gameplay fresh and exciting.

🎨 **Visual Feedback**: Enjoy ASCII art stages that illustrate game progress and player status.

⚙️ **Duplicate Tracking**: Efficient guess management, avoiding redundant inputs from users.

🧠 **Logic Practice**: Perfect for beginners to sharpen control flow, conditionals, and loops in Python.

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.x installed on your machine
- Basic understanding of terminal/command line

### 📥 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/hangman-game-python.git
cd hangman-game-python
````

2. Ensure the following files are present:

```
hangman.py
hangman_words.py
hangman_art.py
```

3. Run the game:

```bash
python hangman.py
```

---

### ▶️ Usage

* Launch the script using Python
* Enter one letter per guess
* Avoid repeating guesses; it warns without deducting lives
* ASCII stages show your current hangman status
* Win by revealing all letters or lose after 6 wrong guesses

---

### 🧪 Testing

You can test by:

* Guessing all correct letters to win
* Guessing incorrect letters to check stage visuals
* Repeating letters to verify no life loss

---

## 🌟 Features

* Modular code using:

  * `hangman_words.py`: Word bank
  * `hangman_art.py`: Logo and stages
* Displays remaining lives after each guess
* Clearly indicates winning or losing conditions
* Tracks already guessed letters
* Clean visual feedback in console

---

## 🗂️ Project Structure

```
hangman-game-python/
│
├── hangman.py           # Main game logic
├── hangman_words.py     # Word list used in the game
├── hangman_art.py       # ASCII visuals and game logo
└── README.md            # Project documentation
```

---

## 🔄 Game Flow

1. Logo is printed from `hangman_art.py`
2. A random word is chosen from `hangman_words.py`
3. The word is masked using underscores
4. Loop:

   * Prompt for input
   * Check if already guessed
   * Update correct letters
   * Deduct a life if incorrect
   * Print current word status and hangman stage
5. End:

   * If all letters are revealed → **YOU WIN**
   * If lives reach 0 → **YOU LOSE** and show correct word

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

*Enjoy coding and hangman-ing!*

```
