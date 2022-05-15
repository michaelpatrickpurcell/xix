# XIX
An 18-card strategy game for two players.
XIX is intended for players who are at least eight years old.

## Overview
Test

## Components
  - **Numbered Cards** (18): One card for each whole number between one and eighteen.

## Set Up
  1. Shuffle all of the cards together.
  2. Deal six cards face down to each player.
     - You may look at your cards but not your opponent's cards.
  3. Place five cards face down on the table in a single row.
     - This row of cards is called the _talon_.
  4. Discard the last card.
     - You will not use this card during the game.

## Playing the Game
A game of XIX consists of a series of _exchanges_.

Each exchange consists of a series of _tricks_.
Both players will play one card in each trick.
Each trick will be _taken_ by either you or your opponent.

You can win an exchange by taking three tricks or by forcing your opponent to abandon the exchange.
At the end of each exchange, points will be awarded to the player who won the exchange.

After each exchange, you will redistribute the cards that were played during that exchange via a draft.

The game ends when either player can deduce which card was discarded in Step 4 of the set up.

You win if you have more points than your opponent at the end of the game.

### Hands
Throughout the game, both players will mange two hands of cards:
  - **Closed Hand**: These cards are kept secret from your opponent. You should hold these cards so that you can see the faces of the cards but your opponent cannot.
  - **Open Hand**: These cards are not secret. You should place these cards face up on the table in front of you.

You will begin the game with six cards in your closed hand and zero cards in your open hand.

When you draft cards, you will add the cards that you draft to your open hand.

Whenever you play a card, you may play a card from either your open hand or your closed hand.

### Tricks
Both players will play one card in each trick.
You play a card by placing it face up in the middle of the table.
Whenever you play a card, you may play any card from either of your hands.

If you won the previous trick, then you will go first.
Otherwise, you will go second.
You should randomly determine which player will go first in the first trick of the game.

If the face values of the two cards played in a trick add up to nineteen, then the second player takes the trick. Otherwise, the player who played the card with the highest face value takes the trick.

### Strikes
If you lose a trick then you receive a _strike_.

When you receive a strike you must do one of the following:
  - **Abandon the Exchange**: You lose the current exchange. Points will be awarded to your opponent.
  - **Raise the Stakes**: Keep playing the current exchange. Increase the number of points that will be awarded to whoever wins the current exchange.

When you receive your third strike, you cannot raise the stakes. You must abandon the exchange.

If you lose an exchange then points will be awarded to your opponent.

### Scoring
The number of points awarded depends on the total number of strikes that have been received during the exchange.
| Strikes | Points |
|---------|--------|
| 1 | 1 |
| 2 | 3 |
| 3 | 6 |
| 4 | 10 |
| 5 | 15 |

#### Example
test

### Drafting
After each each exchange, you will redistribute the cards that were played during the previous exchange via a draft. You will take turns choosing cards, one at a time, until all of the cards have been drafted.
If you lost the previous exchange then you will choose first in the draft.

When you draft a card, add it to your open hand. Once a card has been played during the game, it will remain face up for the remainder of the game.

After the draft, if you lost the previous exchange then you must trade a card from your open hand (your _hand card_) for a card in the talon (the _talon card_). If possible, the talon card must be face down.

If the talon card is face down, add it to your closed hand. Otherwise add it to your open hand.
Place your hand card face up in the talon in the same position that the talon card occupied before the trade.

<!-- If your hand card is from your closed hand, then it is placed face down in the talon. If your hand card is from your open hand, then it is placed face up in the talon. In either case, your hand card is placed in the same position in the talon that the talon card occupied before the trade. -->

After you have completed the draft, you will begin the next exchange.
Whoever won the previous exchange will lead the first trick in the next exchange.

#### Example
test

### Ending the Game
The game ends after the first exchange during which either player can deduce the identity of the unused card which was discarded in Step 4 of the set up.

Notice that if all of the cards in the talon are face up and your opponent's open hand is empty, then you can deduce the identity of the unused card. If either condition does not hold, i.e. if one or more cards in the talon is face down or your opponent's closed hand is not empty, then you cannot deduce the identity of the unused card. A similar analysis holds for your opponent.

So, an equivalent way to state the game-end condition is that the game ends after the first exchange during which all of the talon cards are face up and at least one player's closed hand is empty.
