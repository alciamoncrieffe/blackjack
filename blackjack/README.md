
![BlackJack Logo](https://www.seekpng.com/png/detail/819-8194226_blackjack-instant-game-logo-graphic-design.png)
## Description / Motivation

Blackjack single player game created in python as an OOP project. 

Using the supplied packages and local terminal, play against the automated *Dealer*.

 Current functions allow for both the player and dealer be dealt 2 cards to start. The player then has to choose to **hit** (be dealt an additional card) or **stick** with the hand (cards) they have. The aim being to have a total cards value higher  than the *dealer's* without going over 21.

Deal new hands within the same game and the game will keep score of total wins/loses. 

## Installation

### Dependencies
- Python (>= 3.7)

### User installation

 The easiest way to install blackjack_am is using  `pip`
`pip install -U blackjack_am`

## How to play

In your console, once the blackjack_am package has been installed, type `python` to start the interpreter.
- `new_game = Game('Sarah')` - In your terminal create a new instance of the Game, adding your name as the new player.

- `new_game.deal_cards()`- To deal initial 2 cards to both player and dealer.

Based on the total card values of your and the dealer's cards you then need to decide whether to ...
-  `new_game.hit()` because your cards sum is low and you can probably add a new cards without going over 21

or
-  `new_game.stick()` because your total value is already close to 21 and the dealer is unlikely to get any closer 

You can `.hit()` as many times as you want before you bust (go over 21), but once you choose to `.stick()` the round is over and the results and score will be shown.

To play another round just `.deal()` a new hand for the same instance of game.

**Note**: Blackjack rules allow the card type **Ace** to take the value of 1 or 11. So if the player has an ace in their hand the sum of cards will display both totals [total cards sum assuming the ace = 1,  total cards sum assuming the ace = 11].

## Contributing

Feel free to create new branches or contribute. 
I had intended to add other functions for betting, multiple players, and maybe to allow a player to 'split' their hand. 

## Licensing

See backjack_am package license.txt file.