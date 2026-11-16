# 🃏 Matching Card Game

A browser-based memory matching game project designed to challenge players' concentration, memory, and problem-solving skills.
Live Link: https://matching-card-dwdm.onrender.com

## 🎯 Project Overview

The goal of this project is to create a memory game featuring 10 cards (5 matching pairs).

Players select two cards at a time and attempt to find matching pairs. Matching cards remain face-up, while nonmatching cards flip back over.

The game is completed when all five pairs have been successfully matched.

<img width="960" height="505" alt="image" src="https://github.com/user-attachments/assets/10d9cc20-98d4-46f6-aa38-0ce0cbd60f84" />


## ✨ Game Features

The intended game functionality includes:

- **Interactive cards:** Players select cards to reveal their hidden values.
- **Matching logic:** Compare two selected cards to determine whether they match.
- **Card flipping:** Matching cards remain visible, while unmatched cards flip back over.
- **Memory challenge:** Players remember previously revealed cards to improve their chances of finding pairs.
- **Win condition:** The game ends when all 10 cards have been matched.

## 🛠️ Technologies

The game is intended as a frontend development exercise using:

| Technology | Purpose |
|---|---|
| HTML5 | Structure the game board and cards |
| CSS3 | Style the cards and visual layout |
| JavaScript | Implement card selection, matching logic, and game state |
| Git & GitHub | Version control and project management |


## 🎮 How to Play

1. Start the game with 10 face-down cards.
2. Click a card to reveal its hidden value.
3. Select a second card.
4. If both cards match, they remain face-up.
5. If they do not match, both cards flip back over.
6. Continue selecting pairs until all cards have been matched.

**Objective:** Match all five pairs to complete the game.

## 🧠 Game Logic

The matching system is designed around the following process:

1. Track the first selected card.
2. Allow the player to select a second card.
3. Compare the values of the two selected cards.
4. Keep matching cards revealed.
5. Flip unmatched cards back over after a short delay.
6. Prevent already matched cards from being selected again.
7. Check whether all five pairs have been matched.

