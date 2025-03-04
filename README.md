# Blackjack

## Summary
This Python script is a text-based implementation of the classic card game Blackjack (also known as 21). The game allows the player to compete against a dealer, with the goal of achieving a hand value as close to 21 as possible without exceeding it. The game includes features such as handling Aces (which can be worth 1 or 11), dealer logic for hitting or standing, and win/lose conditions. The game also supports replayability, allowing the player to play multiple rounds.

## Features
- **Random Card Dealing**: The `random` module is used to simulate drawing cards from a deck, with values ranging from 1 to 11.
- **Ace Handling**: The game dynamically handles Aces, allowing the player to choose whether an Ace should be worth 1 or 11. The dealer's Ace handling is automated based on the dealer's current score.
- **Game Logic**: The game includes logic for the player to hit (draw another card) or stand (end their turn). The dealer follows standard Blackjack rules, hitting until their score reaches at least 17.
- **Win/Lose Conditions**: The game checks for win/lose conditions, including busting (exceeding 21), Five Card Charlie (automatically winning with 5 cards totaling 21 or less), and comparing player and dealer scores.
- **Replayability**: The game allows the player to play multiple rounds by prompting them to play again after each round.
- **ASCII Art**: The `art` module is used to display a logo or visual element at the start of the game, enhancing the user experience.
- **User Input Handling**: The game uses `input()` to capture player choices and `.upper()` to standardize input.
- **Conditional Statements**: The game employs `if`, `elif`, and `else` statements to handle player and dealer decisions, as well as win/lose conditions.
- **Loop Control**: A `while` loop is used to manage the game flow, allowing the player to hit or stand and the dealer to draw cards until their score meets the criteria.

## How to Play
1. Run the script in a Python environment.
2. When prompted, enter `Y` to start the game.
3. Follow the on-screen prompts to choose whether to hit (draw another card) or stand (end your turn).
4. The game will automatically handle the dealer's turn and determine the winner based on the rules of Blackjack.
5. After each round, you can choose to play again or exit the game.

## Requirements
- Python 3.x
- The `art` module (for displaying the game logo).

## Running the Game
To run the game, simply execute the script in your Python environment:
```bash
python blackjack_game.py
