# Pocket Game: The Gathering

## Idea

The card management from Magic: The Gathering and head to head action in a pocket game.

## Components

* The 18 cards found in this repository
* (Optionally) counters for lives and tokens

## Rules

### Important Concepts

#### Ready and exhausted
A card can be either 'ready' or exhausted'.
Usually a card can only be used if it is in a ready state.
When readying a card, it is turned to face the player vertically.
When exhausting a card, it is turned to face the player horizontally -- or lie down.

### Setup

Shuffle the 18 cards and place them face down on the table as a draw pile.
If ever the draw pile runs out of cards during a game, shuffle the discard pile and place it face down on the table as a new draw pile.

Each player draws a single card from the deck and places it face down in front of them.
Then each player draws three cards to form their starting hand.
Starting with the first player, each player may discard as many cards as they would like to draw that many new cards from the deck.

Each player start the game with 20 life points.

Then the players alternate taking turns, starting with the first player.

### Player turn

During a player's turn they first ready their cards.
Then they may play cards from their hand and attack with creatures.
Lastly they perform cleanup and draw a card.

#### Ready
At the beginning of a player's turn they will ready all cards in front of them.

#### Playing a mana source
Once during a player's turn they may play a card from hand unto the table as a mana source.
In order to do this, a player takes a card in their hand and places it face down in front of themselves in a ready state.

#### Playing cards
A player may play a card from their hand to get its effect.
Some cards stay on the table -- these are called permanents.
Other cards have an immediate effect and are then discarded.

In order to play a card, a player must announce the intention to play a card by putting it on the table.
Then the player will pay the required amount of ressources for that card.
Then the opposing player may react if they have a reaction available.
And lastly the player playing the card execute the card effect if any.

When playing a card a player must announce which part of the card is being played -- top or bottom.

When paying for a card players must exhaust mana sources equal to the number in the top right corner of the played card.
There are separate numbers for each part of the card -- use the number for the declared effect.
The amount of resources required to play a card is reduced by 1 for each permanent that player controls of the same suit.

#### Attacking
A player may declare attacks during his turn.
Only reaction cards can be played during the attack, from both players.
After the attack the acting player may declare another attack or play more cards.

In order to attack, the attacking player nominates one or more creature permanents he controls as the attacking force.
Then the opponent assigns creature permanents as a defending force.
Each creature in the defending force must be assigned to a single creature in the attacking force.
Multiple defenders can be assigned to one attacker.

Each creature deals damage to its power divided amongst creatures it is fighting.
All creatures deal damage at the same time.
If a creature suffer damage equal to its toughness, that creature is removed from play and discarded.

If an attacking creature does not have any defending creatures assigned, it will deal damage equal to its power to the defending player.

All attackers which are still on the board are then exhausted.

#### Cleanup and draw
All creatures damaged during this round will heal to full at this point.

When a player is done attacking and playing cards, that player must remove one of their unspent unstable mana sources.
A removed unstable mana source will be flipped face up and placed in the discard pile.
A player may look at the front of his unstable mana sources before determining which to discard.

Finally the player draws a card from the deck and play passes to the other player.

### End of the game

The game ends when one player reduces the other player to 0 life points.
The player with life points remaining is the winner.

### Advanced concepts

#### Spells
All cards are spells when they are being played.
When a card is on the table it will have the type indicated on the card itself.

#### Instants
Some cards have the instant type.
Instant cards can be played in the openents turn.
Instants are always played as reactions to something the opponent did and the card will state when it can be played.

#### Suit
Each card belongs zero or more suits as indicated by the card itself.
Suits are used for ingame effects.
