![Memory Card Game](https://res.cloudinary.com/dkqu2s9gz/image/upload/v1730660810/hbnejj44whuxpfexvcn3.png)

# Memory Card Game

This project is a memory card game. The goal is to match pairs of identical cards by flipping them over, completing all pairs in the shortest time and with the fewest moves.

## Features

- **Card Matching Mechanic**: The user selects two cards at a time. If the cards match, they stay face-up on the board; if not, they flip back down.
- **Scoring System**: The game calculates a final score based on the number of moves taken.

## Code Structure (JavaScript)

- **Card Creation and Shuffling**: All cards are created in an array, shuffled, and then placed on the board in random order.
- **Card Flipping**: When the user clicks a card, it flips over. After two cards are selected, they are checked for a match.
- **Match Checking**: If the two selected cards match, they remain face-up; if not, they flip back down.
- **Game End and Scoring**: Once all pairs are matched, the game ends and a score is calculated based on the total number of moves.

## Game Logic

In each turn, the player selects two cards. If the selected cards match, they stay face-up on the board; otherwise, they flip back down. The game ends when all cards are matched, and the score is calculated based on the number of moves taken.

