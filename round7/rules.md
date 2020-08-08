Infinite Nomic Round 7 Rules 

# Rule 1: Information 
The game is a board game, played on a virtual board. A representation of the board shall be kept in a google sheets file, linked to in #game-rules.

# Rule 2: Turn order
When someone becomes a player, their name is put at the bottom of the list of players in #game-rules. Players take turns according to this list, starting with the player on the top of the list and going down. When the player at the bottom of the list has taken their turn, players keep taking turns from the top again. The game begins immediately when the first player joins the game. 

# Rule 3: What happens on a turn
A player's turn consists of optionally making a proposal and having it voted on, and performing any other actions the rules require them to perform on their turn, as well as optionally performing any other actions the rules allow them to perform on their turn. A player may choose to end their turn at any time during it, by stating their intent to do so in #public-forum). If a player does not make a proposal within 24 hours of the start of their turn, they automatically end ("pass") their turn. 
When a player's turn ends, the turn of the player below them in the list in #game-rules begins simultaneously. 

# Rule 4: Proposing and voting
On their turn, a player may make a proposal by posting a message in #proposals. Players may then react to that message with either thumbsup or thumbsdown during the next 24 hours. When the voting period is over, the player's turn ends, and if the message has more thumbsup reactions than thumbsdown reactions, the events stated in the proposal take effect. The rules are maintained on github, which is referred to by a link in #game-rules. 

# Rule 5: The game board
The initial gameboard has 10 spaces, inclusively numbered 1 through 10. Each space is adjacent to the spaces whose numbers are one greater than or lower than its own number, and the space with the highest number is adjacent to the space with the lowest number. This means that a player on the highest space on the game board moving 1 space "up" will move back to space 1 (given that it is the lowest number on the game board). All players are always located on one of the board's spaces. Initially, all players are on space 1.

# Rule 6: Acting in the appropriate channel
For an action other than voting or making a proposal to be effective, it must be announced in #public-forum.

# Rule 7: Moving 
Up to once their turn, a player may move "up" the board, that is, in the direction in which the numbers of the spaces increase. To move, a player announces they are moving and rolls 1d6 in #public-forum. They move exactly that many spaces up the board. 

# Rule 8: Points and the board tiles
All players have an integer associated with them called "points". 
Who has what amount of points is tracked in the list of player names in #game-rules. 
Upon becoming a player for the first time, a player has 0 points. 
When a player lands on a space divisible by 5, they gain 10 points. 

# Rule 9
Tile #4 of the board becomes an "Unlucky Space". 

A player who rolls a 4 on any dice counts as if they landed on an Unlucky Space, no matter the location of the player on the board.

If a player lands on an Unlucky Space, they either: 
a.  move back to tile #1 of the board. This does not count as if they have lapped around the board and gone past tile #10, and instead acts as a regression. 
OR:
b.  lose 5 points. If the player landed on tile #4, they stay on tile #4 with no further effects. If the player rolled number 4, they move to their destination ('p+4', where p is the players position before having rolled a 4) with no further effects.
A player can choose between option a or b when landing on an Unlucky Space.

b is not an option if points are not implemented, non-functioning or state otherwise.
