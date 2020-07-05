# 1. On Rules and Rule Changes 

Each *rule* has an ID number, a title, and a body (a string of text). If a rule ever lacks a title or has an empty title, a moderator can assign a title to it at any time.

No two rules can have the same ID number. If there is general consensus that a rule has a specific ID number, that rule's ID number is set to the consensus, regardless of what it previously was.

# 2. On Proposals and Turn Order 
A proposal is a document designated as such by the rules. 
Each *proposal* has an ID number, a title, and a body (a string of text).   

When a proposal is adopted, it takes effect and any actions described in its body are carried out, except as explicitly prohibited by a rule. A proposal cannot take effect if it has not been adopted in accordance with the rules. Proposals can have neither retroactive nor future effect, even if their text explicitly states otherwise. No proposal may refer to a player or group of players by any non-changing uniquely identifiable or real-life characteristic such as name or nickname, to give them exclusive advantages or disadvantages.

A player submits a proposal by posting a text message labeled as such (which does not refer to a document) in #proposals.
When submitting a proposal, a player shall label it with its ID number. 
Each proposal's ID number is determined at the time it is submitted, and is the number after the previously submitted proposal's ID number (or else 1, if there was no previous proposal).

# 3. Proposing and voting

The legislation process is broken up into two parts, proposal days and voting days. 
There are three proposing groups, group A, group B, and group C.
When a player joins the game, they are randomly assigned to a group already containing not more than 1/3 of the players.

A player's proposal quota is 2 if, during their group's previous proposal day, they submitted a proposal that was later adopted, and otherwise 1.  On their group's proposing day, each member of that group may submit a number of proposals not exceeding their proposal quota; any excess proposal is illegal.

This proposal can be edited ONLY during that groups proposing day. Editing or deleting the proposal's message on its voting day renders it illegal. The proposal still exists for counting and proposing limit purposes.

The following day(s), all players may vote on the submitted proposals by reacting with a thumbs up (👍) or thumbs down (👎) emoji.  
Voting ends simultaneously with the start of the next proposing day, at which time all legal proposals that have a ratio of over 50% positive votes are adopted sequentially in the order they were proposed.
The weekly schedule is as follows:

Monday: Proposing day for Group A

Tuesday: Voting day for Group A proposals

Wednesday: Proposing day for Group B

Thursday: Voting day for Group B proposals

Friday: Proposing day for Group C 

Saturday: Voting day for Group C proposals

Players who have been assigned to a new group for any reason may only propose during that groups proposing day if they did not propose in their previous group's proposing day that week.

# 4.  Score

Each player has a score, measured in points. 
When a player enters gameplay, their score is 0 points. 

If only one player has proposal(s) pass at the end of a voting day, that player may gain 3 points. 

The first player(s) to reach 100 points or more wins the round, also causing the round to end.

When a proposal passes, the proposal's creator may choose to gain 1 extra point for each consecutive passed proposal they created before it.

Other parts of this rule or other rules notwithstanding, no player may gain points in any way while in debt.

# 5. Dad coin
Dad Coin is the currency of this round. A Dad Coin is earned by creating a proposal that is passed.

If a player gains Dad Coins and fails to update their nickname within 48 hours, the gained Dad Coins are forfeit.

A player may have fewer than 0 Dad Coins, in which case that player is "in debt". A player who is in debt cannot win the game, other rules notwithstanding. Being in debt may prevent a player from performing certain actions.

# 6. Error Correction 

Moderators can make changes to the bodies of rules in order to fix obvious grammatical or spelling errors, so long as the changes do not affect interpretation of the rules in any way.

# 7. Actions

Actions are events that can be triggered by players, through publicly specifying their intent to perform it.

Each Action has 3 attributes: a name, a cooldown and a body of text which states what happens upon the triggering of said Action. 
An Action's cooldown is an integer that represents the multiplication of 24 hours a player has to wait until they can perform the same Action again. 
Any commands in an Action's body must be performed by the player who triggered the Action for its effects to occur. 

Actions can only be defined in this rule. Following is a list of Actions: 

Action: Give  
Cooldown: 1  
When this action is triggered, one or more entities belonging to the player performing the action—either dad coins, or any other entity which is explicitly described in the rules as being transferable—are transferred to another player.
When triggering this action, a player must ping the player to whom they are giving something, state what they are giving them, and in what quantity.
This action may not be triggered by a player who is in debt. 
 
Action: Bonus Sunday proposal  
Cooldown: 6  
If today is Sunday, lose 2 Dad Coins and make a proposal. The proposal can be voted on until the end of the same day, and must be created before 12:00 PM UTC

Action: Initiate Contract  
Cooldown: 1  
Ping one (and only one) player with whom you do not already have an active contract and propose your contract. If the pinged player agrees to the terms, and neither party has voided a mutual contract  before, then the contract is initiated.

Once both players have fulfilled their respective parts of the contract, the contract is terminated. While the contract is still in effect, if a player fails to fulfil the conditions imposed on them by the contract within the specified amount of time, then that player loses 20 points and the other gains 15 points. If and when that happens, the contract is immediately terminated.

Action: Nap  
Cooldown: 1  
The player performing this action gains 1 point at the end of the day as long as they did none of the following during the day:  
*Performed any other action  
*Done anything factorially  
*Made a proposal  
 
# 10. Factories and Modules
Each player owns a factory, which produces Points and Dad Coins. The
channel #factories shall be used for all business related to
factories. Whenever any rule states that a player can do something
"factorially", that means that they can only do that thing by stating
that they do so in the #factories channel.

There are items called Modules, which exist to upgrade factories. Each
module has a Name, a Cost, a Description, and an Effect. If a module has no name it defaults to "Placeholder" with a number following it that is 1 for the first module with an empty name and is a subsequent number for each following module. If a module has no cost, it's invalid and can not be purchased. Additionally, if a module only lists a number as its cost, it's that number of Dad Coins. If a module has no description, its description is an empty string. If a module has no effect, it's invalid and can not be purchased. Players can factorially purchase a module that is not unique and they do not already own by paying that module type's cost. This creates a module of that type in their possession. The modules a player owns are transeferable and should be tracked.

Once per week on either Monday or Tuesday, each player can factorially
equip a module to their factory. Factories cannot have more than one module
equipped at any given time. Any action that would cause a factory to
have more than one module equipped is ineffective. At the beginning of
every Monday all modules are unequipped from all factories.
The modules a player owns should be tracked. Unequiped modules are transferable.

Once per week on either Saturday or Sunday, each player can collect from
their factory factorially. The effects of this are decided by which
module they have equipped.

A player may hire other players to work in their factory. To do so, the player doing the hiring and the player being hired must both indicate their agreement factorially. If and when a player collects from their factory, they receive one additional point for each player in their employ, and each player in their employ receives one Dad Coin. 

A player may hire multiple other players to work in their factory, but no player may work in more than one factory at a time. A player may not hire themselves to work in their own factory. A player may fire any of their employees or quit their job by announcing it factorially.

Modules can be unique. Unique modules have a cost of 0 and must specify that they are unique in their respective effects.

Every time a proposal is adopted that introduces at least one new unique module to the game, an auction for each one of those modules starts. During an auction, players may bid on the corresponding module by factorially stating the module's name and naming an amount of Dad Coins that is higher than zero and can be expressed as an integer. 
For each auction, once at least one bid has been placed and the highest bid is 24 hours old, then the auction ends. The player who placed the largest bid becomes the owner of the corresponding module and loses an amount of Dad Coins equal to the highest bid they placed. A player may not hire any employees on Saturday or Sunday.

The following types of modules are defined:

**Name**: Default  
**Cost**: Free  
**Description**: *This is the normal, unoptimized factory.*  
**Effect**: When collecting from this module's factory, gain 5 Points. 
Lose an amount of Dad Coins that is lower than 4, given that it would not cause your Dad Coin balance to go below 0. For every Dad Coin you choose to lose, gain 5 additional points. 

**Name**: Pointer  
**Cost**: 1 Dad Coin  
**Description**: *For a small price, you can double your weekly output!*  
**Effect**: When equipping this module to a factory, pay one Dad
Coin. When collecting from this module's factory, gain 10 Points.
Lose an amount of Dad Coins that is lower than 4, given that it would not cause your Dad Coin balance to go below 0. For every Dad Coin you choose to lose, gain 5 additional points. 

**Name**: Atomic Engine  
**Cost**: 1 Dad Coin  
**Description**: *Not sure what we did to this one, but it works!
Sometimes...*  
**Effect**: When collecting from this module's factory, generate a
random number between 1 and 3. If 1, lose 5 Points. If 2 or 3, gain 10
Points.
Lose an amount of Dad Coins that is lower than 4, given that it would not cause your Dad Coin balance to go below 0. For every Dad Coin you choose to lose, gain 5 additional points. 

**Name**: Point-O-Matic 3000  
**Cost**: 3 Dad Coins  
**Description**: *This cutting-edge (and expensive) technology is hard
to get a handle on, but your investment will pay off in just weeks!*  
**Effect**: When equipping this module to a factory, pay one Dad Coin.
When collecting from this module's factory, gain 2 Points for each
consecutive past week you have collected from this factory with this
module equipped to it (to a maximum of 20 Points).
Lose an amount of Dad Coins that is lower than 4, given that it would not cause your Dad Coin balance to go below 0. For every Dad Coin you choose to lose, gain 5 additional points. 

**Name:** The Moneymaker  
**Cost:** 3 Dad Coins  
**Description:** *You gotta spend money to make money.*  
**Effect:** When equipping this module to a factory, pay 1 Dad Coin. When collecting from this module's factory, gain 3 Dad Coins.
Lose an amount of points that is lower than 16, given that it would not cause your point balance to go below 0. For every 5 points you choose to lose, gain 1 additional Dad Coin. 

**Name:** Father Frack  
**Cost:** 1 Dad Coin  
**Description:** *Your trusty pa is back to help you frack that sweet sweet Dad Coin, make your pappy proud.*  
**Effect:** When equipping this module to a factory, pay 2 points. When collecting from this module's factory, gain 2 Dad Coins.
Lose an amount of points that is lower than 16, given that it would not cause your point balance to go below 0. For every 5 points you choose to lose, gain 1 additional Dad Coin.

**Name:** The Legislator
**Cost:** 2
**Description:**  
**Effect:** While you have this module equipped, gain 1 point every time a proposal passes. When collecting from this module's factory, gain 1 Dad Coin for every player under your employ who passed a proposal.

# 11. Player Tracking
The annex of a nickname is the final parethenesized section of that nickname (example: in "Mr. X (1, 3)", the annex is "(1, 3)"). Nicknames shall contain no parentheses other than those that introduce or terminate the annex. The annex shall appear at the end of a nickname. The fields of an annex are parts separated by commas (example: in the annex "(1, 3)", the fields are "1" and "3").

Certain quantites are described as player-tracked. Each player shall record their current values of player-tracked quantities in the annex of their nicknames, but shall not be punished for recording values that were correct up to 48 hours ago. If, at any time, a player's nickname has an incorrect value of a player-tracked quantity, a moderator may update that player's nickname to reflect the correct values.

If a player-tracked quantity in a player's nickname deviates from the true value by a non-zero constant, and has deviated from the correct value by that same constant for at least 72 of the previous 96 hours, that quantity is updated so that the player's nickname is correct.

# 12. Tracked Values
Score is a player-tracked quantity. Dad coins balance is a player-tracked quantity.

Each player's annex shall be of the form "($P, $M$C)", where "$P" is their score, "$M" is one or more characters acting as a currency symbol, and "$C" is their dad coin balance.

# 13. Judges

Every week starting on Monday, any player may become a candidate for the next Judge by sending a text message in the channel #judge-elections. Immediately after the week ends, the player whose post has the most thumbs up reactions becomes the Judge for a week. 
If there is a tie, then an alphabetic list of the tied players is made and the first player on that list is this week's new Judge.

Any player other than the current Judge may at any time ping the Judge and pose a question concerning any set of ambiguous, unclear, or conflicting rules.
 The Judge may then send a text message in #judge-rulings that will settle how the rule ought to be interpreted. The Judge's ruling goes into effect exactly 24h after it is posted. If it's deleted, or the ratio of thumbs down to thumbs up for that ruling is 3:2 or higher, then that ruling does not go into effect. Judges may not edit their rulings, though they may override them by creating a new ruling.

Only declarations of candidacy may be posted to #judge-election, and only one per player per week. Only the current Judge may send messages in the channel #judge-rulings.

Every Judgment posted by the Judge must include a link to the discord message that requested the Judgment. If the Judgment does not, it does not go into effect.
