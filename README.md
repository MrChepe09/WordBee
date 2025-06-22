# 🐝 WordBee — A Wordle-Inspired Game Built with React

Welcome to **WordBee** — a fun and challenging 5-letter word guessing game built using React!  
Test your vocabulary, logic, and strategy as you try to guess the hidden word within 6 attempts.

---

## 🎮 How to Play

- Guess the **5-letter English word** in **6 tries**.
- Each guess must be a valid word **with no repeating letters**.
- Feedback is given in the form of:
  - 🟢 **Green**: correct letter in the correct position.
  - 🟠 **Orange**: correct letter, wrong position.
  - ⚪ **Gray**: incorrect letter.
- Numbers beside each row show:
  - The count of 🟢 correct-position letters.
  - The count of 🟠 misplaced-position letters.

---

## 🛠 Tech Stack

- ⚛️ **React.js** — Frontend framework
- 🎨 **CSS** — Responsive styling and layout
- 🧠 **Custom Logic** — Valid word filtering, guess checking, and game state management

---

## ✨ Features

- 🔄 New game generation with unique 5-letter target words
- 🔠 Smart input navigation for seamless typing
- 🧮 Feedback circles and count display
- 📱 Fully responsive for mobile and desktop
- 🚫 Prevents duplicate letter guesses and invalid words

---

## 📂 Folder Structure

```
src/
├── App.jsx              # Main game component
├── wordList.js          # Full word list used for validation and target selection
├── filteredWordList.js  # List with only unique-letter 5-letter words
├── styles/              # Optional custom CSS
```

---

## 🧪 Future Improvements

- 🔊 Sound effects for feedback
- 📊 Stats & streak tracking
- 🌎 Dark mode toggle
- 🌐 Language support

---

## 👩‍💻 Authors

- [MrChepe09](https://github.com/MrChepe09)

---

## 📄 License

MIT License — feel free to use, modify, and share.

---

Happy Guessing! 🐝💛
