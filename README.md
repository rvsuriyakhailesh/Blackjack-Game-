# Blackjack-Game-
This repository contains a simple text-based Blackjack game implemented in Python. The game allows you to play against the computer, simulating the classic card game of Blackjack. The objective is to get as close to 21 points as possible without going over.

Features
Random Card Dealing: Cards are dealt randomly from a standard deck.
Score Calculation: The game calculates the score based on the cards dealt, with special rules for Aces.
Game Logic: Includes logic for handling different game scenarios such as Blackjack, busts, and draws.
User Interaction: Prompts the user to hit or stand, and displays the current and final hands and scores.
Replay Option: Allows the user to play multiple rounds in a single session.
How to Play
Start the Game: Run the script and follow the prompts.
Initial Deal: Both the player and the computer are dealt two cards.
Player’s Turn: The player can choose to ‘hit’ (get another card) or ‘stand’ (end their turn).
Computer’s Turn: The computer will draw cards until it reaches a score of at least 17.
Determine Winner: The game compares the scores and announces the winner.
Code Overview
deal_card(): Returns a random card from the deck.
calculate_score(cards): Calculates the score of a given hand of cards.
compare(user_score, computer_score): Compares the user’s score with the computer’s score and determines the result.
play_game(): Manages the flow of the game, including dealing cards, handling user input, and determining the winner.
