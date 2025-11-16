# Simon Game - Web Implementation 🕹️

[▶️ **Play Live Demo Here**](https://yxp23.github.io/simon-game-js/)

## 💡 Overview
This is a web-based implementation of the classic electronic Simon memory game. The player must successfully repeat an increasingly complex pattern of colored buttons and sounds.

## 🛠️ Technologies Used

* **HTML5 & CSS3:** For the game structure and styling (including the retro-style "Press Start 2P" font).
* **JavaScript (jQuery):** Used for managing the game logic, handling user interaction, and controlling the sequence flow.
* **Audio API:** For providing immediate sound feedback for both the computer's pattern and the user's input.

## ✨ Implementation Highlights
This project was built to demonstrate proficiency in core web development concepts, including:

* **Game State Management:** Implemented variables (`gamePattern`, `userClickedPattern`, `level`, `started`) to effectively track the game's progress and state.
* **Asynchronous Logic:** Utilized `setTimeout()` to introduce necessary delays, allowing the user to view and hear the computer's sequence clearly before their turn begins.
* **Event Handling:** Used jQuery to cleanly detect user input (`$(".btn").click`) and initiate the game (`$(document).keypress`).
* **Complex Logic Flow:** Implemented the `checkAnswer()` function to recursively validate the user's input against the correct sequence after every click.

## 🚀 How to Play
1.  Open the game in your browser.
2.  Press any key to start.
3.  Watch the pattern (colored button flashes and sounds) demonstrated by the computer.
4.  Repeat the pattern by clicking the buttons in the correct order.
5.  If you make a mistake,the screen flashes red, and the game resets, challenging you to beat your previous level!

**Author: Yash Patil**
