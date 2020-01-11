# UNO-Card-Game-Hackathon-
CUHacking Hackathon Event January 11, 2020

Date: January 11, 2020
Team members: Andy, Brenda, Luis, Navady

PSEUDOCODE FOR THE UNO PROJECT

There are 108 cards in the game.

Making various objects:
CARD OBJECT:
- Colour (R, G, B, Y)
- Rank (0 - 9)
- Special (Draw 2 cards, Skip, Reverse)
- Wildcard, Wildcard 4

PLAYER OBJECT:
- Player number
- Card[] 
- Number of cards

Game flow:
Assign a player a random player number.
Place 1 card in the middle (the current card)
Distribute 7 cards to each player (up to 4)
The players take turns placing cards into the middle (following UNO rules)

If a player has 1 card remaining, that player must call 'UNO!' to be safe.
If another player calls 'UNO!' before this player, this player must draw 1 extra card from the deck.

If a player has 0 cards remaining, that player wins and the game is over.


