# Fate/Draw: Strike

## Overview

This is a TCG for the fate universe in which you take on another master with your servant in a deck you have perfected. Using features and servants from your favorite servants is what makes this game special. It is a solo indie development project that is made just to practice and gain experience within the Unity engine.

## Game Mechanics

These are the core fundamental mechanics of a TCG to be implemented into the game

### Feature 1: The Format

Each Player will be able to have a deck of cards. They will both draw 5 cards. A coin will then be flipped to decide who goes first. First player will always be one mana ahead, second player will draw 1 extra card. The idea is that whoever goes first will always have the opportunity to play a card first, but whoever goes second will have more options.

### Feature 2: The Cards

The cards will have 3 main components: MP (Mana Points which is the cost), AP (Attack Points) and GP (Guard Points). Cards can also have effects/conditions attached to them to make them unique which will be described below. Servant Cards will all have a quest which when completed will unlock the true potential of the servant, allowing for their Holy Phantasm to be activated and also raising stats of AP/GP

### Feature 3: Card Keywords

This will be a set of keywords for the special features that could be added to cards or that cards may innately possess. Servants can also have these keywords attached to them, but they cannot gain keywords from cards that may grant keywords.

- Stealth: The card will be hidden and only those who are stealth or have the vigilant trait can attack
- Barrier: The card has X tokens of barrier added on to it's GP status. Barrier points are removed upon taking damage
- Pierce: Half of a card's AP will go through a card's GP to directly attack a player's HP
- Double-Strike: The current card will strike twice in a row on the same target. If the target is destroyed on the first strike then the card will strike the player directly
- Taunt: The card with the taunt status will be forced to be block first before other cards can be blocked
- Vigilant: This card can see through stealth units, Vigilant cards also gain +1 AP if they destroy a Stealth card

## Game Identity

These are the features that make this game unique and place it into the fate universe. Most notably these will include 3 core things: Servants, Command Seals, and Holy Phantasms

### Feature 1: Servants (0%)

The game revolves around summoning servants as your main unit or powerhouse of the deck. This game will use a mana system like most other TCGs with every servant costing the same mana to summon. Much like other TCGs, your servant will have a quest attached to them that you can complete to then upgrade them to their final form and unlock the use of their Holy Phantasm.

### Feature 2: Command Seals (0%)

A big part of the Fate universe is the idea of command seals. Typically denoted as 3 per servant summoned, a master has 3 commands that are to be performed by their servant with complete obedience. I intend to implement Command Seals as a way to act using instants in this game instead of the normal variation of having instant spells. That way you have to really think about the command seal cards (instants) you decide to play in a game.

### Feature 3: Holy Phantasms (0%)

These are powerful cards that can only be played once you have your servant card summoned and upgraded. These cards can cause massive shifts in the tide of battle and can easily decide the victors of games. They're not a OHKO win condition though as command Seals will have the power to block a lot of incoming damage should you be careless in throwing out this attack
