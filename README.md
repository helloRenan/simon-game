# 🧠 Simon Game

Welcome to the Simon Game repository! This project is a simple implementation of the classic Simon memory game built using **HTML**, **CSS**, and **JavaScript**. The purpose of this project is to learn and practice JavaScript fundamentals, with a particular focus on jQuery for DOM manipulation and event handling.

---

## 📚 How the Game Works

1. **Sequence Generation**: A random sequence of colors is generated. The sequence starts with one color and increases in length after each round.
2. **Player's Turn**: The player must replicate the sequence by clicking the corresponding colored buttons in the correct order.
3. **Game Over**: If the player clicks an incorrect button or fails to replicate the sequence correctly, the game ends. The game will then display the score and the player can try again.

---

## 📌 Features

- **Random Sequence**: The game generates a random sequence of colors that grows with each round.
- **Dynamic UI Updates**: The colored buttons light up and play sounds corresponding to the sequence.
- **Score Tracker**: Displays the player's score, which is the number of correct rounds completed.
- **Sound Feedback**: Each button has an associated sound that plays when clicked.
- **Responsive Layout**: The game interface is responsive and adjusts well to various screen sizes.

---

## 💻 Technologies Used

- **HTML**: For structuring the game layout and content.
- **CSS**: For styling the game buttons and overall design.
- **JavaScript**: For handling game logic, sequence generation, and event tracking.
- **jQuery**: For easier DOM manipulation, event handling, and animations.

---

## 🎮 How to Play

1. Open the `index.html` file in a browser (or deploy the page online).
2. A sequence of colors will light up one by one.
3. Click the colored buttons in the exact order as they light up.
4. If you replicate the sequence correctly, the sequence will grow, and you'll move to the next round.
5. If you make a mistake, the game will end and show your score.

---

## 📦 Getting Started

To get started with the game, simply clone this repository to your local machine:
```bash
git clone https://github.com/helloRenan/simon-game.git
```
Once you have the project files, open `index.html` in your browser to start playing!

---

## 📁 Project Structure

```graphql
Simon Game/
│
├── index.html        # The main HTML file
├── style.css        # The CSS file for styling the game
├── game.js        # The JavaScript file that contains the game logic
└── sounds/          # Folder containing sound files for button clicks
```
**index.html**: Contains the structure of the game interface, including the clickable buttons.
**style.css**: Adds styles for the buttons, layout, and animations.
**game.js**: Handles the game logic, including the sequence generation and player interaction.
**sounds/**: Contains the sound files played when the buttons are clicked or the game ends.

---

## 👥 Contributing

If you'd like to contribute to this project, feel free to submit a pull request with any improvements or bug fixes. All contributions are welcome!

---

## 🔗 License

This project is open source and available under the [MIT License](LICENSE).

---

Enjoy the game and have fun mastering JavaScript and jQuery!
