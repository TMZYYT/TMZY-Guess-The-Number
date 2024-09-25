# TMZY's Guess the Number Game

Welcome to the "Guess the Number" game! In this simple and fun web game, players try to guess a randomly generated number between 1 and 100. The game provides feedback on whether the guess is too high or too low, and a "Start Over" button allows players to replay after a successful guess.

## Table of Contents
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Contributing](#contributing)
- [Versions](#versions)

**Installation**

To run the game on your local machine:

Clone the repository:

Open the HTML file:

Navigate to the directory where the repository was cloned and open the latest file in a web browser.


**How to Play**

*Start the Game:*
The game will display a prompt asking you to guess a number between 1 and 100.

*Make a Guess:*
Enter your guess in the input box and click the "Guess" button.

*Receive Feedback:*
The game will inform you if your guess is too high, too low, or correct.

*Restart the Game:*
Once you guess the number correctly, a "Start Over" button will appear, allowing you to play again without refreshing the page.


**Contributing**
If you'd like to contribute to this project, feel free to submit a pull request or open an issue for suggestions or improvements!


## Versions

### Version 1: TGTN-v1
- **Description:** Initial version of the game featuring basic HTML and CSS.

### Version 2: TGTN-v2
Description: Combined HTML, CSS, and JavaScript into a single file for a more interactive experience.

### Version 3: TGTN-v3
- **Description:** Added a "Start Over" button that appears after a correct guess, allowing players to restart the game easily.

  
### **Code Snippet:** 
```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TMZY's Guess the Number Game</title>
    <style>
        /* CSS styles here */
    </style>
</head>
<body>
    <div class="game-container">
        <h1 class="game-title">TMZY's Guess the Number</h1>
        <p>I have chosen a number between 1 and 100. Can you guess it?</p>
        <input type="number" id="guessInput" placeholder="Enter your guess">
        <button onclick="guessNumber()">Guess</button>
        <p id="feedback"></p>
        <button id="startOver" onclick="startGame()" style="display: none;">Start Over</button>
    </div>
    <script>
        // JavaScript logic here
    </script>
</body>
</html>
