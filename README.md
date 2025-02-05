# 🎩 Hangman - The Classic Word Guessing Game

Welcome to **Hangman**, a fun and interactive word-guessing game built in Python! Test your vocabulary, challenge your friends, and try to guess the word before the hangman is fully drawn! 🚀

## 📌 Features
✅ Classic Hangman gameplay
✅ ASCII art-based hangman stages 🖼️
✅ Word selection from a predefined list
✅ Tracks guessed letters and words
✅ Play again option

---

## 🎮 How to Play
1. The game randomly selects a word from a list.
2. You have **6 chances** to guess the correct word.
3. You can guess **one letter at a time** or try guessing the entire word.
4. If the guessed letter is correct, it is revealed in the word.
5. If incorrect, you lose a try and the hangman figure progresses.
6. Keep guessing until you either guess the word or run out of tries.
7. Win by guessing the word before the hangman is fully drawn!

---

## 🚀 Installation
To run this game on your local machine:

1. **Clone this repository**
   ```sh
   git clone https://github.com/yourusername/hangman-game.git
   ```

2. **Navigate to the project folder**
   ```sh
   cd hangman-game
   ```

3. **Install Python (if not installed already)**
   - [Download Python](https://www.python.org/downloads/)

4. **Run the game**
   ```sh
   python hangman.py
   ```

---

## 📸 Game Preview
```
Let's play Hangman!
---------
|       |
|
|
|
|
|
-
_ _ _ _ _ _

Please guess a letter or word:
```

---

## 🛠️ Project Structure
```
📂 hangman-game/
│── hangman.py          # Main game script
│── words.py            # List of words for the game
│── README.md           # Project documentation (this file)
```

---

## 🎨 ASCII Hangman Stages
Each incorrect guess brings you closer to defeat:
```
6 tries left:
  ---------
  |       |
  |
  |
  |
  |
  -

0 tries left (Game Over):
  ---------
  |       |
  |       O
  |      \|/
  |       |
  |      / \
  -
```

---

## 🏆 Contribution
Want to improve this project? Feel free to contribute!
1. Fork the repository 🍴
2. Create a new branch 🚀
3. Implement your changes ✨
4. Submit a pull request 📩

---

## 📜 License
This project is **open-source** and available under the [MIT License](LICENSE).

🚀 **Enjoy Playing Hangman!** 🎩

