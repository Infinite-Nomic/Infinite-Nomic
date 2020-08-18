Infinite Nomic Round 7 Rules 

# Rule 1: Information 
The game is a board game, played on a virtual board. A representation of the board shall be kept in a google sheets file, linked to in #game-rules.

# Rule 2: Turn order
When someone becomes a player, their name is put at the bottom of the list of players in #game-rules. Players take turns according to this list, starting with the player on the top of the list and going down. When the player at the bottom of the list has taken their turn, players keep taking turns from the top again. The game begins immediately when the first player joins the game. 

# Rule 3: What happens on a turn
A player's turn consists of performing any actions the rules require them to perform on their turn, as well as optionally performing any other actions the rules allow them to perform on their turn. A player may choose to end their turn at any time during it, by stating their intent to do so in #public-forum). A player's turn autmatically ends ("passes") 24 hours after it started. When a player's turn ends, the turn of the player below them in the list in #game-rules begins simultaneously. If a player ends their turn, they have 1 hour to ping the next player whose turn it is, or they will lose 1 point. This only counts if you have done something on your turn (I.e. moving)

# Rule 4: Proposing and voting
A player who does not already have a proposal being voted on may make a proposal by posting a message in #proposals. Players may then react to that message with either thumbsup or thumbsdown during the next 24 hours. When the voting period is over, if the message has more thumbsup reactions than thumbsdown reactions, the events stated in the proposal take effect. The rules are maintained on github, which is referred to by a link in #game-rules. If a proposal message is deleted or edited before it takes effect, then the proposal is retracted. It does not take effect and its voting period ends.

# Rule 5: The game board
The gameboard consists of the spaces defined in the rules. All players are always located on one of the board's spaces.

The gameboard has a number of primary spaces, *n*, inclusively numbered 1 through *n*. Each primary space is adjacent to the primary spaces whose numbers are one greater than or lower than its own number, and the primary space with the highest number is adjacent to the primary space with the lowest number.

# Rule 6: Acting in the appropriate channel
For an action other than voting or making a proposal to be effective, it must be announced in #public-forum.

# Rule 7: Moving 
Up to once on their turn, a player located on a primary space may move "up" the board, that is, in the direction in which the numbers of the spaces increase (wrapping around if they reach the highest-numbered primary space). To move, a player rolls 1d6 in #public-forum. They move exactly that many spaces up the board. A player's turn ends if within five minutes of moving they do not explicitly declare that they are continuing their turn.

# Rule 8: Points and the board tiles
All players have an integer associated with them called "points". 
Upon becoming a player for the first time, a player has 0 points. 
When a player lands on a space divisible by 5, they gain 10 points. 

# Rule 9
Cop Car is a space feature. Initially, space 4 has this feature.

If a player lands on a space with a Cop Car, they must, within 5 minutes of their roll, choose one of the following options (otherwise the first option is taken automatically):

a. admit fault, moving to the jail space; OR
b. bribe the officer, losing 5 points. Their turn ends immediately (not an option if points are not implemented or non-functioning).

If a player rolls a 4 on their turn, then, after moving, the space that previously had the Cop Car feature loses that feature and the player's current space gains it.

# Rule 10
There is a non-primary space named Jail. A player who is in Jail may not move on their turn. While a player is in jail they may roll 1d6 up to once on their turn, if the player rolls 5 or 6, they are no longer in jail and are placed on space 1.

# Rule 11
Each space on the gameboard has a number of features on it. Types, locations, and effects of features are defined by the rules.

When a player lands on a space with a feature, all the effects of its features are applied in alphabetical order by feature name. This order can be modified by the rules.

Feature effects can only take place after a player moves.

# Rule 12
The primary space with the highest number is also known as "The Frontier". If a player is on the The Frontier, when they move up the board, they explore new territory: when the player rolls to move, they subtract one from the number, and move that many spaces into the unknown, expanding the board by that many spaces as they go. Then the final space of their move returns them to space 1.

# Rule 13
When a player lands on or passes space 1, they gain 5 points.
