Rule 1: Resources
-----------------

There exist six types of resources in the game: Ore, Fuel, Carbon, Food, Science, and Trade Goods. By default, each player starts off with no resources. Rules may define ways to obtain, spend, and/or lose resources. A player may not spend more resources than they have, and unless another rule specifies otherwise, a player may not possess more than 2 of each resource at one time. 

Each player's resources shall be tracked in a GitHub document named "Cargo-Hold".

Whenever a player's proposal passes, that player receives one Trade Good.

Rule 2: Ships
-------------

Each player that joins the game is given a ship.  All ships have the following statistics (also referred to as the ship's "C-DSP"):

========== ====
Class      \(C)
Durability \(D)
Speed      \(S)
Power      \(P)
========== ====

By default, the ship given to each player is a "Model-One" class ship, that has 1D 1S and 1P as the default statistics. 

All rules that define a new Ship class must also define that Ship class' default DSP. The status of each player's Ship shall be tracked in a Github document called 'Ships'.

If a rule states a players Ship is destroyed, the player is immediately issued a new "Junker" class Ship with default characteristics 0D 0S 0P. This rule designates all players whose Ship has ever been destroyed as losing the game.
