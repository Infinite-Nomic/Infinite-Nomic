Rule 1: Resources
-----------------

There exist six types of resources in the game: Ore, Fuel, Carbon, Food, Science, and Trade Goods. By default, each player starts off with no resources. Rules may define ways to obtain, spend, and/or lose resources. A player may not spend more resources than they have, and unless another rule specifies otherwise, a player may not possess more than 2 of each resource at one time. 

Each player's resources shall be tracked in a GitHub document named "Cargo-Hold".

Whenever a player's proposal passes, that player receives one Trade Good.

Rule 2: Ships
-------------

Every active player has a ship. All ships have the following statistics (also referred to as the ship's "C-DSP"): 
Class (C) 
Durability (D) 
Speed (S) 
Power (P). 
Ships also have titles, but titles do not count as statistics. However, Ship titles are still noted next to a Ship's statistics, along with the name of that Ship's owner. A Ship's default title is the name of its class. 
A player may request to change a Ship's title by saying so explicitly in a channel and mentioning the Ship's new title (an @Archivist ping must also be included in the request). 
The request to change a Ship's title is not valid if the Ship is not your own or if another Ship already has said title. 

If a player has no ship and has never had a ship before, they are given a "Model-One" class ship that has 1D 1S and 1P as the default statistics.

If a rule states a players Ship is destroyed, the player is immediately issued a new "Junker" class Ship with default characteristics 0D 0S 0P. This rule designates all players whose Ship has ever been destroyed as losing the game. Any Ship that has less than zero Durability is immediately destroyed.

All rules that define a new Ship class must also define that Ship class' default DSP. The status of each player's Ship shall be tracked in a Github document called 'Ships'.

Rule 3: Trading
-------------

Players can request to trade with other players by pinging them in #trading-centre (a trading specific text channel). A trade can only be an exchange of 1 Trade Good for 1 of any other resource, and both players must agree to the trade. Once a trade has been agreed to, a Moderator or Archivist must also be pinged to update the Cargo-Hold.

Rule 4: Dice rolls as Standardized Variability
-------------

Should the need for variability arise, a player, rule, or any other game effect can call for a "dice roll" to determine the outcome using Beldum-Bot#8256's //rng command.

Three variables must be provided for a diceroll:
X (Goal number)
Y (Minimum  number)
Z (Maximum number)

The command for a dice roll is //rng Y,Z where Y and Z are replaced with the variables mentioned above.  The value of the result can be changed by any rule or game effect that specifically says it changes the value of the result. 

If the value of X is the letter "N",  the value of the result is the final value of the dice roll.  If the value of X is a number, and the value of the result meets or exceeds it, the dice roll is a "Pass", otherwise it is considered to be a "Fail".

Rules may also specify other results outside of, or in addition to, "Pass" and "Fail", or include clauses that override specific results.

Rule 5: Ship upgrades
-------------

A player can buy upgrades for their ship when and only when a player and their ship is docked at a space station. The names, costs (in resources) and effects of all available upgrades are specified in this rule in the form of a list. The adding or removal of upgrades are done by amending this rule. All upgrades have the effect described in this rule at the moment.

Upgrade 1: 
Name: Extra Cargo Space. 
Cost: 2 Ore and 1 Carbon. 
Effect: A ship with Extra Cargo Space may carry one extra resource of each type at any given time.

Upgrade 2:
Name: Even More Cargo Space.
Cost: 3 ore, 2 carbon, 2 science.
Effect: This upgrade can only be purchased if your Ship already has Extra Cargo Space. A ship with Even More Cargo Space may carry one additional extra resource of each type at any given time.

Upgrade 3: Holodeck Luxury Suite.
Cost: 2 ore, 2 food, 2 carbon, 2 science.
Effect: none.

Upgrade 4: Synthetic Fiber Captain's Chair.
Cost: 3 fuel, 3 carbon, 3 trade goods, 3 science.
Effect: This upgrade can only be purchased if your Ship already has Holodeck Luxury Suite.

Upgrade 5: Gold Plated Hull.
Cost: 4 food, 4 fuel, 4 trade goods, 4 ore, 4 science.
Effect: This upgrade can only be purchased if your Ship already has Synthetic Fiber Captain's Chair, and only if no other Ship has Gold Plated Hull. This rule designates the Player whose Ship has Gold Plated Hull as winning the game.

Rule 6: Rulings
-------------

When there is a question as to the interpretation of the rules, any player may request a ruling by pinging a @moderator in a channel and describing what they would like clarification on. Any @moderator may issue the requested ruling before the end of the next full Legislative Day by posting it in the appropriate section of the the rules documentation. If no @moderator issues a ruling by this time, the player requesting the ruling may do so by posting it in a channel and pinging an @archivist to perform the update.

Although they are posted in the rules documentation, rulings are not considered rules and may only be used to clarify rules that already exist. Once issued, however, rulings are considered legal precedent and must be adhered to with the same weight as the rule or rules they are clarifying.

Rule 7: Deckbuilding
-------------

Define a new entity called a "Card Class", and also define objects called "Cards" and "Piles". Card Classes have two properties: A name; and an associated event (called an Effect). Cards are instantiations of Card Classes; rules may create, destroy, move, or otherwise interact with cards as desired. Each Card is associated with exactly one Card Class. If a Card Class is repealed, all Cards associated with it cease to exist. A Pile is a collection of cards. A Card at any given moment must be in exactly one Pile; if at any time it is associated with no Pile, for example because the Pile it was part of was removed, the Card ceases to exist. (Cards may be moved from one Pile to another without ceasing to exist.) Players are entitled to know the contents of all Piles.

There exists a Pile called the Deck, and another called the Discard. The cards in each collection shall be tracked in a Github document called "Deck". Both of these Piles start off empty. When a Card is created, it starts off in the Discard unless specified otherwise.

Rules may define ways to Activate cards and to Draw cards. Effects that Activate cards must specify a "Subject" player. If a Card is Activated, the procedure detailed in its Effect is obeyed.

When a rule states to Draw a card from a Pile, a random Card is selected from the Pile by generating a random number X from 1 to N, where N is the number of Cards in the Pile, and then selecting the Xth card from the top of the list. That rule can then activate it, move it, etc. as outlined in the rule description.
.

A player “Encountering a card” shall be shorthand for the following procedure:

* If no Cards are in the Deck or the Discard, end this procedure; nothing happens.
* If no Cards are in the Deck but at least one Card is in the Discard, move all cards from the Discard to the Deck.
* Draw a Card from the Deck, Activate it, and then move it to the Discard. The player who is Encountering shall be designated as the Subject of the Card’s Activation.

Current players may voluntarily Encounter a Card once each time they are given the Current role.

Rule 8: Card Class Creation Proposals
-------------

Card Class Change Proposals are defined as a proposal that creates, or deletes one Card Class or amends one or more attributes of one Card Class.

A Card Class Change Proposal that creates a Card Class must specify the details of a Card Class required by other rules. (At the time of this rule's creation, a Card Class must have a name and an Effect, and thus a Card Class creation proposal must specify these things.)

If the Card Class Change Proposal is accepted, then the Card Class it modifies is changed accordingly, and then one new Card of that Card Class is created and added to the Discard pile, unless a different number is specified, in which case that many cards are created instead.

Rule 9:  The Map
-------------
A Github file labeled "The-Map" is created, with a coordinate system that has both an X and Y axis.  The-Map is considered a direct extension of this rule, and as such can be amended at the same time as this rule. Each coordinate pair contains one Feature slot, which is empty by default, but can be filled by a Feature as defined by this or other rules. Each Feature must include a name, and may include additional effects. Coordinate pairs are referred to with the following format:

Coord (X,Y)

A discord channel labeled "#space" is created. The only allowed messages in #space are messages that are specifically required to be sent in #space. 

All active players' ships have a location, which can be any coordinate pair that exists. Ships can change their location by moving along the X or Y axes. Each players ship location is stored in "The-Map" under a table titled "Ship Location". Once a day, each player is able to move up to a number of values equal to their speed, split between either axis however they wish. They can make these movements by posting their initial and final coordinate pairs in the channel #space in this format:

Moving  Ship from (X,Y) to (X,Y)

Positive and negative value movement are identical, and a player cannot gain additional movement by moving positively on one axis, but negatively on another. 

If at any point an active player's ship does not have a location, it is automatically given a location of Coord (1,1) 
 
The following coordinate pairs exist: 
 
Coord (1,1) , Coord (2,1), Coord (3,1)

Coord (1,2) , Coord (2,2), Coord (3,2)

Coord (1,3) , Coord (2,3), Coord (3,3)


Coord (1,1) has the following "Feature":

Space Station: 
Any ship that shares a location with this Space Station is considered Docked. Each day any ships that are Docked at the Space Station may gain 1 Fuel by posting the message "Refueling my ship" in #space.


Rule 10: Piracy
-------------

If a player's ship is in the same location as another player's ship, then either player may choose to spend one Carbon to attempt to steal the other's cargo.

A player making said attempt (the pirate) must indicate clearly which player (the victim) they are stealing from. The victim of the attempt can choose to either surrender, and give 2 resources from their cargo hold to the pirate, or to fight back.

If the victim chooses to fight back, then both players generate a random number between 0 and their ship's power.

If the victim's number is higher, then the pirate's ship loses 1 durability.
If the pirate's number is higher, then the victim must give 1 resource from their cargo hold to the pirate, and the victim's ship loses 1 durability.
If the numbers are equal, then nothing happens.

If a victim does not respond within 24 hours of a pirate declaring their intent to steal, then the victim automatically surrenders.

Players may not commit piracy while docked at the space station.



Rule 11: To Explore Strange New Worlds
----------------

A player may move their Ship to a coordinate pair which does not exist if the coordinate pair consists of two integers AND the coordinate pair would be legal to move to if it existed. When this happens, the coordinate pair is added to existence; also, the player who moved to the new coordinate pair automatically Encounters a Card (this is not optional).
