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

If a rule states a players Ship is destroyed, the player is immediately issued a new "Junker" class Ship with default characteristics 0D 0S 0P. This rule designates all players whose Ship has ever been destroyed as losing the game.

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
