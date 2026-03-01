# Tic Tac Toe

A classic Tic Tac Toe game built using HTML, CSS, and JavaScript. This project allows two players to play the popular game in the browser with interactive UI, real-time win/draw detection, and easy game resetting capabilities.

## Demo

[Link to Live Demo](https://amxo.netlify.app/)

## Features

- **Two Player Mode:** Playable by two players taking turns ("O" and "X").
- **Win Detection:** Automatically highlights when a player gets 3 marks in a row (horizontally, vertically, or diagonally).
- **Draw Detection:** Detects and announces if all boxes are filled and no one has won.
- **Reset & New Game Options:** Easily clear the board to start a new game at any time or after a game finishes.
- **Responsive & Clean UI:** Simple and aesthetically pleasing design.

## Technologies Used

- **HTML5:** Structure of the web page.
- **CSS3:** Styling, flexbox layout, and interactive box aesthetics.
- **JavaScript (ES6):** Game logic, event handling, and DOM manipulation.

## Project Structure

```
├── index.html   # The main HTML document containing the game layout/structure
├── style.css    # The stylesheet with UI styling and animations
├── app.js       # The JavaScript file handling the game rules and logic
└── README.md    # This documentation file
```

## How to Run

1. Clone this repository or download the project files.
2. Open the project folder.
3. Simply double-click on the `index.html` file to open it in your default web browser.
4. Start playing!

## How to Play

1. Player 1 starts as **"O"** and Player 2 is **"X"**.
2. Click on any empty box on the grid to place your mark.
3. Players take alternate turns.
4. The first player to align 3 of their marks horizontally, vertically, or diagonally wins the game.
5. If all 9 boxes are filled and no player has 3 marks in a row, the game ends in a Draw.
6. Click the "Reset" button during the game or "New Game" when it finishes to play again!
