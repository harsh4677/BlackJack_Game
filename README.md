# Blackjack Game

Welcome to the Text-based Blackjack Game in Python!


## Introduction

This is a simple implementation of the classic Blackjack card game in Python. In this game, you can play multiple rounds of Blackjack against the dealer and aim to win as many games as possible.

## How to Play

1. **Prerequisites:** Make sure you have Python 3.x installed on your computer.

2. **Clone the Repository:** Clone this repository to your local machine or download the `blackjack.py` file.

3. **Run the Game:**
   - Open your terminal or command prompt.
   - Navigate to the folder containing `blackjack.py`.
   - Run the game by entering the following command:
     ```bash
     python blackjack.py
     ```

4. **Gameplay Instructions:**
   - Specify the number of games you want to play at the beginning.
   - During your turn, choose between "Hit" or "Stand" to make your move.
   - The game will display the results and continue until you've completed the specified number of games.

## Classes

### Card Class

- Represents a playing card with a suit and rank.
- The `__init__` method initializes the card with a suit and rank.
- The `__str__` method returns a string representation of the card.

### Deck Class

- Represents a deck of playing cards.
- The `__init__` method creates a standard deck of 52 cards.
- The `shuffle` method shuffles the deck.
- The `deal` method deals a specified number of cards from the deck.

### Hand Class

- Represents a player's or dealer's hand in the game.
- The `__init__` method initializes an empty hand.
- The `add_card` method adds one or more cards to the hand.
- The `calculate_value` method calculates the hand's total value.
- The `get_value` method returns the current hand value.
- The `is_blackjack` method checks if the hand has a Blackjack.
- The `display` method displays the hand's cards and value.

### Game Class

- Manages the main game logic.
- Allows players to play multiple rounds of Blackjack.
- Determines the winner and handles player choices.

## Future Improvements

- Adding betting functionality.
- Allowing multiple players to join the game.
- Implementing a graphical user interface (GUI) for a more interactive experience.

## Known Issues

- No known issues at the moment.

## Author

- Harsh Salve
- harshsalve2782003@gmail.com

Feel free to contact the author with any questions, feedback, or suggestions.

Enjoy the game!
