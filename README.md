
## Description
This is a simple implementation of the classic Blackjack card game in Java, utilizing Swing for the graphical user interface. The game allows a single player to play against the dealer.

## Features
- Player can "Hit" to receive an additional card or "Stay" to end their turn.
- Dealer automatically plays according to the rules.
- Ace cards are valued either as 1 or 11, optimizing the player's hand to avoid busting.

## How to Run
1. Ensure you have Java installed on your system.
2. Compile the `BlackJack.java` file.
   ```bash
   javac BlackJack.java
   ```
# Gameplay
1. Upon starting the game, both the player and dealer are dealt two cards.
2. The player can choose to "Hit" or "Stay" based on their current hand.
3. If the player's hand value exceeds 21, they bust and lose the game.
4. After the player's turn, the dealer reveals their hidden card and draws cards until their hand value reaches 17 or higher.
5. The winner is determined based on the hand values:
      If both the player and dealer bust, it's a tie.
      If only one busts, the other wins.
      Otherwise, the higher hand value wins.

## Screenshot

![Blackjack](https://github.com/MeGaTroNOO7/BlackJack/assets/98184459/c77b0b67-5d63-4afe-bf69-5e3d68462931)
