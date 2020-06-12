# 1. On Rules and Rule Changes 

Each *rule* has an ID number, a title, and a body (a string of text). If a rule ever lacks a title or has an empty title, a moderator can assign a title to it at any time.

No two rules can have the same ID number. If there is general consensus that a rule has a specific ID number, that rule's ID number is set to the consensus, regardless of what it previously was.

# 2. On Proposals and Turn Order 
A proposal is a document designated as such by the rules. 
Each *proposal* has an ID number, a title, and a body (a string of text).   

When a proposal is adopted, it takes effect and any actions described in its body are carried out, except as explicitly prohibited by a rule. 
A proposal cannot take effect if it has not been adopted in accordance with the rules. 
Proposals can have neither retroactive nor future effect, even if their text explicitly states otherwise.

A player submits a proposal by posting a text message labeled as such (which does not refer to a document) in #proposals.
When submitting a proposal, a player shall label it with its ID number. 
Each proposal's ID number is determined at the time it is submitted, and is the number after the previously submitted proposal's ID number (or else 1, if there was no previous proposal).

# 3. Proposing and voting

The legislation process is broken up into two parts, proposal days and voting days. 
There are three proposing groups, group A, group B, and group C.
When a player joins the game, they are randomly assigned to a group already containing not more than 1/3 of the players.

A player's proposal quota is 2 if, during their group's previous proposal day, they submitted a proposal that was later adopted, and otherwise 1.  On their group's proposing day, each member of that group may submit a number of proposals not exceeding their proposal quota; any excess proposal is illegal.

This proposal can be edited ONLY during that groups proposing day. Editing a proposal on its voting day or later renders the proposal illegal. 

The following day(s), all players may vote on the submitted proposals by reacting with a thumbs up (👍) or thumbs down (👎) emoji.  
Voting ends simultaneously with the start of the next proposing day, at which time all legal proposals that have a ratio of over 50% positive votes are adopted.
The weekly schedule is as follows:

Monday: Proposing day for Group A

Tuesday: Voting day for Group A proposals

Wednesday: Proposing day for Group B

Thursday: Voting day for Group B proposals

Friday: Proposing day for Group C 

Saturday and Sunday: Voting day for Group C proposals 

Players who have been assigned to a new group for any reason may only propose during that groups proposing day if they did not propose in their previous group's proposing day that week.

# 4.  Score

Each player has a score, measured in points. 
When a player enters gameplay, their score is 0 points. 

If only one player has proposal(s) pass at the end of a voting day, that player may gain 3 points. 

The first player to reach 100 points wins the round, also causing the round to end. 

Players shall keep their score at the end of their nickname in parenthesis (for example, Klink (15)). 

If a player gains points and fails to update their nickname within 48 hours, the gained points are forfeit. 

If a player loses points, and fails to update their nickname within 48 hours, a moderator may update their point total on their behalf within 96 hours of the points being lost. 

When a proposal passes, the proposal's creator may choose to gain 1 extra point for each consecutive passed proposal they created before it.

Other parts of this rule or other rules notwithstanding, no player may gain points in any way while in debt.

# 5. Dad coin
Dad Coin is the the currency of this round. A Dad Coin is earned by creating a proposal that is passed.

Players shall keep the amount of Dad Coins they have at the end of their nickname in parenthesis, preceded by a currency symbol of their choosing (for example, Klink (¥3)).

If a player gains Dad Coins and fails to update their nickname within 48 hours, the gained Dad Coins are forfeit.

If a player loses Dad Coins, and fails to update their name within 48 hours, a moderator may update their Dad Coin total on their behalf within 96 hours of the Dad Coins being lost.

A player may have fewer than 0 Dad Coins, in which case that player is "in debt". A player who is in debt cannot win the game, other rules notwithstanding. Being in debt may prevent a player from performing certain actions.

# 6. Error Correction 

Moderators can make changes to the bodies of rules in order to fix obvious grammatical or spelling errors, so long as the changes do not affect interpretation of the rules in any way.

# 7. Actions

Actions are events that can be triggered by players, through publicly specifying an Action's name and their intent to perform it. 

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
 
# 10. Factories and Modules
Each player owns a factory, which produces Points and Dad Coins. The
channel #factories shall be used for all business related to
factories. Whenever any rule states that a player can do something
"factorially", that means that they can only do that thing by stating
that they do so in the #factories channel.

There are items called Modules, which exist to upgrade factories. Each
module has a Name, a Cost, a Description, and an Effect. Players can
factorially purchase a module that they do not already own by paying
that module type's cost. This creates a module of that type in their
posession. The modules a player owns should be tracked.

Once per week on either Monday or Tuesday, each player can factorially
equip a module to their factory. Factories cannot have more than one module
equipped at any given time. Any action that would cause a factory to
have more than one module equipped is ineffective. At the beginning of
every Monday all modules are unequipped from all factories. The module
equipped to each factory should be tracked.

Once per week on either Saturday or Sunday, each player can collect from
their factory factorially. The effects of this are decided by which
module they have equipped.

A player may hire other players to work in their factory. To do so, the player doing the hiring and the player being hired must both indicate their agreement factorially. If and when a player collects from their factory, they receive one additional point for each player in their employ, and each player in their employ receives one Dad Coin. 

A player may hire multiple other players to work in their factory, but no player may work in more than one factory at a time. A player may not hire themselves to work in their own factory. A player may fire any of their employees or quit their job by announcing it factorially.

The following types of modules are defined:

**Name**: Default  
**Cost**: Free  
**Description**: *This is the normal, unoptimized factory.*  
**Effect**: When collecting from this module's factory, gain 5 Points.

**Name**: Pointer  
**Cost**: 1 Dad Coin  
**Description**: *For a small price, you can double your weekly output!*  
**Effect**: When equipping this module to a factory, pay one Dad
Coin. When collecting from this module's factory, gain 10 Points.

**Name**: Atomic Engine  
**Cost**: 1 Dad Coin  
**Description**: *Not sure what we did to this one, but it works!
Sometimes...*  
**Effect**: When collecting from this module's factory, generate a
random number between 1 and 3. If 1, lose 5 Points. If 2 or 3, gain 10
Points.

**Name**: Point-O-Matic 3000  
**Cost**: 3 Dad Coins  
**Description**: *This cutting-edge (and expensive) technology is hard
to get a handle on, but your investment will pay off in just weeks!*  
**Effect**: When equipping this module to a factory, pay one Dad Coin.
When collecting from this module's factory, gain 2 Points for each
consecutive past week you have collected from this factory with this
module equipped to it (to a maximum of 20 Points).

**Name:** The Moneymaker  
**Cost:** 3 Dad Coins  
**Description:** *You gotta spend money to make money.*  
**Effect:** When equipping this module to a factory, pay 1 Dad Coin. When collecting from this module's factory, gain 3 Dad Coins.  

**Name:** Father Frack  
**Cost:** 1 Dad Coin  
**Description:** *Your trusty pa is back to help you frack that sweet sweet Dad Coin, make your pappy proud.*  
**Effect:** When equipping this module to a factory, pay 2 points. When collecting from this module's factory, gain 2 Dad Coins.  
