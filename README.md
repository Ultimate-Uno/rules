# Introduction
Hi! We're a club that believes in the modification of board games to make the ultimate amalgamation of one. We specialize in adding rules to the popular card game UNO to make it even more fun than it ever was. Our current rules are down below. Check the [commit history](https://github.com/Ultimate-Uno/rules/commits/main) to see how the rules evolved into becoming the Ultimate game of UNO.

# How to read the rules
This rulebook is laid out in a way where unsuspecting players can read special modifications of the rules. 

* Rules in parentheses () mean house rules that the [online UNO game](https://store.steampowered.com/app/470220/UNO/) comes with, special effects that come with the card, or additions to the cards above them. 
* _Italicized_ text means entirely new rules, such as having to roll a dice when you call UNO, and if you roll a number higher than, let's say 3, then your UNO is counted, otherwise draw 2 cards.
* __Bold__ text means new special cards, such as a card that reflects Draw 2 and Wild +4 cards back to the player.
* ~~Strikethrough~~ text means rules that have been omitted.

Anything not formatted in this way is most likely a real UNO rule.

# Adding a rule
This wouldn't be Ultimate UNO without some suggestions! If you want to add or omit a rule, [open a pull request](https://github.com/Ultimate-Uno/rules/pulls) and edit the rulebook to your liking (make sure to follow the "How to read the rules" section) and add a TL;DR in the pull request comment. If your addition to the rulebook is accepted, then congratulations, you are a contributor!

If you wish to add a special card, I (ollin) will design one based on the rules and what you want the card to look like.

# Goal
The first player to play all the cards in their hand wins. ~~in each round scores points for all the cards their opponents are left holding. The first to 500 points wins the game.~~

# Set Up
Each player draws a card. The player with the highest card value is the dealer. Each player is dealt ~~7~~ 5 cards. Place the remaining cards face down in a pile. This will be the DRAW pile. Take one card from the DRAW pile and place it face up next to the DRAW pile to begin a DISCARD pile. If the first face up card from the DRAW pile is a ~~Wild or a Wild +4~~ special card (Skip, Draw +2, Wild, etc.), put the card back into the draw pile, shuffle it, then try again. 

Each player also draws 2 cards from the magic draw pile.

# Special Cards

* Draw 2 - When player (a) plays this card, the next player (b) must draw 2 additional cards and forfeit their turn. This card may only be played on a matching color or on another Draw 2 card. This card may also be played if you choose to stack (see STACKING below)

(STACKING) - If player (b) has a Draw card, they may choose to play it and make the next player (c) draw the additional cards PLUS the previous number that player (b) had to draw. The amount of cards a player needs to draw will increase by 2 for every turn that a player places a Draw 2. If the last player does not have a Draw 2, they must draw the total of all the Draw cards played when stacking, ending the chain.

* Reverse Card - This card reverses the direction of play. Clockwise turns into counter-clockwise and vice versa. This card may only be played on a matching color or on another reverse card. 

(TRAP CARD) - If you are hit with a Draw 2 or Wild +4, stacked or not, and you have a Reverse, you may play it and roll a 6 sided dice. If the dice shows 4 or above, the player who played the Draw 2 or Wild +4 must draw the cards in full and they will be skipped, leaving the turn back to you. If the dice shows a 3 or below, however, you must draw twice what you need to draw and your turn is skipped. This card may be played on top of another Reverse if your Draw 2 or Wild +4 has been reversed.

* Skip Card - When this card is placed, the next person in line to play will lose their turn and is "skipped". This card may only be played on a matching color or on another Skip card.

(TAKE A CHANCE) - If you are hit with a Draw 2 or Wild +4, stacked or not, and you have a Skip, you may play it and roll a 6 sided dice. If the dice shows 4 or above, the Draw 2 or Wild +4 (or stacking, if that is the case) is passed to the next person in full. If the dice shows 3 or below, however, you must draw twice what you need to draw and your turn is skipped. This card may be stacked on top of another Skip if the draw has been passed to you.

* Wild Card - When you play this card, you may change the top color of the DISCARD pile into any color. 

(CRAZY NUMBERS) - However, you must roll a 10 sided dice. The number that appears after the roll will become the number of the Wild.

* Wild +4 - This is the same as the Wild Card but requires the next player to draw 4 cards and forfeit their turn. 

~~(BLUFFING) - However, this card may only be played if you do not have any other card to play. The player required to draw 4 may challenge the player who played the Wild +4 if they think they played the card illegally. If they are guilty, the player who played the Wild +4 must draw the 4 cards. If not, the player who challenged must draw 4 cards PLUS an additional 2 cards as a penalty.~~

(STACKING) - Similar to the Draw 2 STACKING effect, this card may also be stacked with other Draw cards. The BLUFFING clause does not take effect if this card is being stacked.

* "7 and 0s"  - When you play a 7 of any color, you may swap hands with any person you'd like. If you play a 0 of any color, every players' hands are given to the next person in the direction of play. If turns are going clockwise, everyone passes their cards clockwise, and vice versa.

# Magic Cards
In tradition of making this game as mindbogglingly confusing and hard to learn as possible, we have decided to go with a Yugioh style approach. Introducing: magic cards! A stylish, second hand that allows you, the player, to destroy your opponents with special effects such as an airstrike, anti-UNO, and an Exodia clone! However, this isn't Yugioh. We have also implemented a mana system in order to control how many of these special cards that you can play per turn. 

During the beginning of your turn, you may choose to draw one magic card from the magic draw pile. At the end of your turn (if an UNO card is played or a magic card with the ability to end your turn is played), you must take one mana. Jump-Ins automatically exclude you from the last 2 rules mentioned unless you jumped in on yourself.

To view a list of every card featured in Ultimate Uno, click [here](https://github.com/Ultimate-Uno/rules/blob/main/CARDS.md).

Here are the types of cards we feature:

* Spell Cards - The most common card in the magic card series. These cards have the ability to affect anyone and anything at the table, as written on the card. The amount of mana needed to use the card is determined by its rarity (see PRICES below).

(SINGLE SPELL) - Only one of these cards are needed to use them.

(DOUBLE SPELL) - Two of the same card is needed to use it.

(ATTACK SPELL) - Any spell that can attack another player, defined by the sword emblem.

(CHANCE SPELL) - Any spell that requires a dice roll to function, defined by the dice emblem.

(DEALER SPELL) - Any spell that can add or remove cards, defined by the +2 emblem.

(SEATED SPELL) - Any spell that affect a normally untouchable part of the game (such as switching seats), defined by the table/pi emblem.

* Trap Cards - These cards must be set before they can be activated. They have the ability to do something when the condition(s) written on the card are met. To set the card, place it face down and put two mana on top of it. They can be activated at any time when the condition(s) are met, even if it isn't your turn. You may unset the card to take the mana back, but it cannot be activated after being unset.

(COUNTER TRAP) - Normally activated when something or someone is threatening you, and it can essentially reflect that attack back at the threat.

* Field Effects - These cards have the ability to change anything at the table. They stay in effect until (a) A condition on the card is met or (b) another field effect is played. Only one field effect at a time can be played, unless stated otherwise 😏

(TIMED EFFECT) - A field effect that will expire after a condition is met, defined by the clock emblem.

(INFINITE EFFECT) - A field effect that stays in play indefinitely until another field effect is played, defined by the infinity emblem.

(CHANCE EFFECT) - A field effect that requires a dice roll to function, defined by the dice emblem.

* Special Parts - On their own, they are useless, but when paired with their counterparts, they can do some serious damage. The only use of this type is the Exodia clone, or formally known as The Ultimate Wild. Collect all 5 parts, pay 5 mana, and you win.

* Penalty Cards - When drawn, the effect immediately activates, usually causing the player to draw from a dice roll. This is why you can choose to draw a magic card!

* Equipable Spells (WIP) - These cards come in a set of 3 or more and are drawn from a separate pile. Once all parts of the set are retrieved, you can trade those parts in for a singular card that acts as all those pieces and invest some mana for special perks.

* Equipable Attacks - These cards can be attached to __any__ ~~attack type~~ spell (including other players') and the card shows how much mana to attach.

# Playing
The player to the left of the dealer plays first. Play passes clockwise. You must match the top card of the DISCARD pile with either a matching color or matching number. For example, if the top card is a Red 5, you must play a red card, any color 5, or any Wild card. If you do not have a matching card, you must draw. If you draw a card you can play, you may play or keep the card. If no one is out of cards by the time the DRAW pile is depleted, reshuffle the DISCARD pile and continue play.

(DRAW TO MATCH) - If you do not have a card to play or choose to draw, you must keep drawing until you draw a card you can play. When you draw a card you can play, you may choose to play the card or keep it. Normally you would want to play it, it's better to have 26 cards than 27.

(JUMPING IN) - If you have the same color and number as the top of the DISCARD pile, you may play it out of turn before the next person in play. Play continues after the person who jumped in.

_(MAGIC CARDS)_ - You may choose to draw a magic card in the beginning of your turn. As explained in the magic cards section, you may play a magic card during your turn, assuming you have enough mana for that card.

# Going out
Before playing your next to last card, you must say "UNO". If someone catches on that you did not say "UNO", then you must draw ~~4~~ 2 cards as a penalty. You can only get caught after you play your second to last card and before the next player's turn. Once a player plays their last card, the hand is over and they win. 
