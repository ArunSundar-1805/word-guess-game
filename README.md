# Word Guess Game

A fun and interactive word guessing game built with React and Vite. Challenge yourself to guess the hidden word in a limited number of attempts!

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Gameplay](#gameplay)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project is a single-player word guessing game, similar to popular games like Wordle. The player must guess a secret word by entering guesses, receiving feedback about correct and incorrectly placed letters. The game offers a simple yet engaging interface, making it suitable for casual play or for building your React skills.

## Features

- Interactive word guessing gameplay
- Real-time feedback on guesses (letter matches, correct/wrong positions)
- Responsive interface built with React
- Unlimited play: refresh for a new word
- Supports custom word lists for enhanced replayability
- Easy to extend with additional features (timers, scoring, difficulty levels)

## Gameplay

1. The game randomly selects a word from a predefined or custom word list.
2. The player enters a guess using provided input fields.
3. After each guess, the game displays feedback:
   - Correct letters in the correct position
   - Correct letters in the wrong position
   - Incorrect letters
4. The player continues guessing until the word is found or attempts run out.
5. A new word is generated on game restart.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ArunSundar-1805/word-guess-game.git
   cd word-guess-game
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```
   or
   ```bash
   yarn
   ```

## Usage

Start the development server:
```bash
npm run dev
```
or
```bash
yarn dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to play.

## Project Structure

- `/src`
  - `App.jsx` — Main game logic and UI
  - `components/` — Reusable React components
  - `assets/` — Static assets and styles
  - `words.js` — Word list used for gameplay
- `public/` — Static files
- `README.md` — This documentation
- `package.json` — Project configuration

## Technologies Used

- **React** – UI framework
- **Vite** – Fast build tool
- **JavaScript** – Core language
- **CSS** – Styling
- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react) – React plugin for Vite

## Customization

- To add more words, edit the `src/words.js` file.
- You can adjust the number of allowed guesses, word length, or add features like scoring and timers in `App.jsx`.
- Styling can be customized in `src/assets/styles.css`.

## Contributing

Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request. For bug reports or feature requests, open an issue.

