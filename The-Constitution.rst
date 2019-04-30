- **1 § On Rules and Rule Changes**

All rules have ID numbers, names, and a body of text, except for the Constitution, which has no ID number.

All active players (See 5§) are bound to follow any provisions given by the text of the rules.

A rule change is an action classified as one of:

1. the repeal of a single rule from the ruleset,
2. the enactment of a single new rule to the ruleset, or
3. the amendment of a single rule currently in effect (changing several parts of one rule counts as one rule change, but changing several rules does not, even if they are of the same class).

Rule changes can be put into effect entities with Legislative Power. Rules and rule change proposals (see 2§) have Legislative Power.

If The Constitution is in conflict with another rule, The Constitution takes precedence.

All proposals that affect The Constitution must include the following note at the top: "(This is a constitutional proposal, and as such requires at least 75% for votes to pass)"

- **2 § On Proposals and Turn Order**

Proposals each have an ID number, a name, and a body of text. Proposals can be either rule change proposals, Archivist application proposals, or any other kind of proposal defined by other rules. When a proposal is passed, any actions described in its text are carried out, except as described elsewhere in the ruleset. When a proposal is failed, none of its actions are carried out in any capacity. Proposals cannot describe changes to happen at any time other than the instant the proposal is passed.

Whenever a player submits a proposal to #proposals, they shall label it with its ID number. Each proposal's ID number is the last proposal's ID number plus one, except for the first proposal of each round, which has the ID number 1, regardless of the previous proposal's ID number.

A rule change proposal describes one or more rule changes (see 1§). Rule changes in rule change proposals can be referred to by the ID number of their main proposal, plus a single letter, which is assigned in alphabetical order based on the order the rule change came in the proposal. If a rule change in a rule change proposal attempts to change something that is irrelevant to the issues addressed by the majority of the proposal, that rule change does not take effect when the proposal is passed. 

Rule change proposals can also specify titles for rules they create and amend. Upon such a proposal being passed, all rule names specified therein are set as described. If a rule ever lacks a title, any Archivist may give it a title at any time.

- **3 § On Legislation**

The legislating process consists of two days, each day stretching from 20:00 CET one day to 20:00 CET the following day. Each such period is called a Legislative Day.

During any Legislative Day, a player who has at least 1 proposal voucher can make a proposal by posting in #proposals. A player can only make one proposal per day, and doing so costs one proposal voucher. The number of proposal vouchers owned by each player are tracked in the GitHub channel "Cargo-Hold". On every Thursday when the game is updated, every active player gains three proposal vouchers. No player may ever have more than 5 proposal vouchers simultaneously.

If it is specified that specific kinds of proposals are subject to special provisions, those provisions take precedence over the standard approvals listed below. Similarly, if it is specified that specific kinds of proposals skip steps of the legislative process, then they immediately go to the next relevant stage of legislation.

Each proposal submitted in #proposals is passed on for a Chamber Vote on the Legislative Day after it is submitted to #proposals.

A Chamber Vote consists of the proposal being posted to #voting with a poll attached. All active players may vote on this poll. Players may only vote For or Against proposals and, unless otherwise specified, may only submit 1 vote per proposal. 

*Ruling by Zephnik, as requested by Klinkplink:* 
*Thumbs up and thumbs down emojis are universally understood as "For" or "Against" in relation to voting.*


The proportion of For votes to total votes required for a proposal to pass is as follows:

1. If the proposal is a rule change proposal that enacts or repeals more than one rule, 75%.
2. If the proposal is a rule change proposal that amends the constitution, 75%.
3. If the proposal is an Archivist application proposal, 75%.
4. If another rule describes a proportion other than the one listed above, that proportion.
5. Otherwise, 50%.

At the end of the Legislative Day on which the Chamber Vote takes place, any proposals that have achieved their relevant thresholds according to this rule are passed and any proposals that have not are failed.


- **5 § On Time Limits and Inactive Players**

A player has to complete all actions mandated by the rules before the end of the next Legislative Day unless stated otherwise. Players who comply with this rule are considered Active.

If a player doesn’t fulfill an obligation compelled by the rules within the time granted for it, they are considered Inactive.

Once a player becomes Inactive, they will be given the "Inactive" role and will be removed from the turn order in #turns.

Inactive players are not permitted to vote, nor are they permitted to access any voting channel.

A player tagged as "Inactive" can make a request to become active again in the #nomic-discussion channel, or by using the command !active. Upon doing so, they are considered active again, the "Inactive" role is removed from them, and they are added in last place in #turns.


- **6 § On Winning and the Game End**

Rules may define ways to win the game. A player winning the game does not end the game immediately. A single rule may not designate more than one winner at a time; if it would designate multiple winners, it designates no winners instead. Winners are given the @winner role for as long as they are designated as a winner by at least one rule. A player may not have the @winner role if a rule designates them as losing the game.

The game may end at any time if either of the following two conditions apply:

1. Three different players are designated Winners concurrently.
2. All active players agree to end the game.

When a rule causes the game to end, the following procedure happens:

1. A message is posted to #announcements declaring the end of the game. This message shall include a ping to @ everyone.
2. All rules outside of the Constitution are immediately and automatically repealed.
3. All non-rule rule entities are deleted.
4. All current @winner players have their @winner role replaced with @crowned .
5. All players automatically become Inactive.
6. Gameplay terminates until at least 48 hours have passed since the announcement of game end.
7. After 48 hours have passed, gameplay begins anew.

If by some clause in this Constitution a situation arises in which an infinite loop of game ending is triggered, the game does not end. Instead, the channel #constitutional-mediation is created, and each active player makes a mediation proposal in #constitutional-mediation to resolve the issue.  The first proposal to reach at least 66% of votes from all active players is placed into effect.  If no proposal receives 66% of votes within 24 hours,  this process repeats until the loop is ended.


- **8 § On Tracking**

Tracking may be performed in either a channel on the Infinite Nomic Discord Server or a file on the official GitHub repository (currently located at https://github.com/klinkplink/Infinite-Nomic). Either type can be called a channel for rules purposes.

In the case of a literal Discord channel, one player shall be designated to track the data in that channel by the rule that mandates the channel's creation. In the case of a file, any Archivist can update the data in that channel.

To be added as an Archivist, a player may submit an Archivist application proposal. When an Archivist application proposal passes, the author will be given the Archivist role and will be added as a collaborator to the GitHub repository


- **9 § On Joining the Game**

When a Discord user joins the server, they are not automatically added to the turns list, and are not considered to be playing the game. The user cannot gain points, vote, propose, or otherwise participate in the game outside of chatting.

To join the game, a user may use the !interested command and ping a @Moderator indicating intent to join. At this point, they are officially recognized as a player, and may be added to the turn list and otherwise allowed to participate in the game.
