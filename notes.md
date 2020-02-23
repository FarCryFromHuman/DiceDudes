New version dump inc:

- Stripped the game down to its core strategy, found something more interesting, i think
- Players don't need boards anymore and the boardstate should be much clearer
- There's now a tile deck, and a market deck
- Players have a collection of pillars in their color, and begin with a handful of power (cubes)
- The dice and player boards are gone

# Tile Deck

- The tile deck is comprised of the set of hex tiles being used for the game
- Each tile has two sides
- Each side has an effect that can be invoked (cantrips, auras, sorceries, and rituals can all exist in this design)
- Each side also belongs to a suit, two suits, or is wild, same as before
- Old rules about adjacency, locking, etc all count
- Scoring rules have changed (explained below)

# Market Deck

- A deck of cards from which a market is stocked (probably players + 1 in size?)
- Players can buy cards to activate them immediately, as one of their actions on their turn
- To buy a card, a player drops power on each card in front of it in line, takes any power on the card, resolves and keeps the card, then slides the market down and restocks
- Market cards have a few unique effects:
  - Scoring: the card will depict a pattern of tiles, and have a point value attached. when a player buys a scoring card, he must own tiles matching the pattern on the card (in any rotation). He chooses a tile belonging to the pattern to remove from the board, takes all power on the tile, returns all pillars on the tile, and discards it from the board
  - Attacking: the card will depict a pattern of attacking tiles and target tiles. when a player buys an attack card, he must have pillars on tiles matching the pattern of the attacking tiles on the card (in any rotation). He then chooses up to one pillar on each tile matching the configuration of the target tiles and returns it. If no pillars remain on an attacked tile, he may optionally take all power from the tile as well. If there is no target tile on the board in one or more positions in the pattern, ignore those tiles for attack resolution.
  - Building: the card will depict a pattern of tiles. when a player buys a building card, he optionally places one pillar on each tile matching the pattern, ignoring tiles missing from the pattern
  - Exploring: the card will have an icon depicting tile placement, and be worth a single point. when purchased, the player places a new tile
  - Apocalypse: may or may not need this, but some form of board reset card that shows up infrequently
- Cards should go face down after bought to prevent score tracking, probably?

# Player turns

- On his turn, a player chooses to meditate or take actions
- If he meditates, he can take any amount of power from any tiles he has pillars on (at the start of his next turn? This way it clears the spaces for him and not a whole round of opponent turns)
- Then, if he doesn't have 10 power, he takes power from the stock until he does
- If he takes actions, he can do 3, from the following list:
  - Invoke: place a power cube on a tile he has a pillar on, and resolve the effect on the tile
  - Buy card: buy a card, as above
- Other design thought: buying cards never takes actions, and you can buy cards and invoke 3x.. probably makes turns too swingy and hard to keep track of though

# Game end

- The game ends when the market deck runs out or there are 4 apocalypses or something
- The winner is the most points on cards + pillars on the board
- Tie can go to most power i guess but i doubt it's necessary
