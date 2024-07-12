# rolePlayingGame
The third project under the FCC JS algorithms and data structures curriculum.
This project is a text-based role-playing game where players can explore locations, fight monsters, and manage their inventory and health.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Gameplay](#gameplay)
- [Functions](#functions)

## Overview

This game allows players to:
- Navigate between different locations (town square, store, cave).
- Buy health and weapons.
- Fight monsters (slime, fanged beast, dragon).
- Gain experience points and gold.
- Win by defeating the dragon or lose by running out of health.

## Features

- Dynamic Interface: The game updates the interface based on the player's actions.
- Inventory Management: Players can buy, sell, and use weapons.
- Combat System: Players can attack, dodge, and run from monsters.
- Easter Egg: A hidden game where players can win additional gold.

## Getting Started

- Clone the repository.
- Open index.html in a web browser.
- Use the buttons to navigate and interact with the game.

## Gameplay

### Locations

- Town Square: The central location with options to go to the store, cave, or fight the dragon.
- Store: Players can buy health or weapons.
- Cave: Players can fight weaker monsters like slime and fanged beast.
- Fight: Players engage in combat with monsters.
- Kill Monster: Players receive rewards after defeating a monster.
- Lose: The game over screen when the player dies.
- Win: The victory screen when the player defeats the dragon.
- Easter Egg: A secret game with a number guessing challenge.

### Actions

- Attack: Engage a monster in combat.
- Dodge: Attempt to avoid a monster's attack.
- Run: Escape from the fight.

### Functions

#### Core Functions
- update(location): Updates the game interface based on the current location.
- goTown(): Navigates to the town square.
- goStore(): Navigates to the store.
- goCave(): Navigates to the cave.
- buyHealth(): Buys health for gold.
- buyWeapon(): Buys a weapon for gold.
- sellWeapon(): Sells the current weapon for gold.
- fightSlime(): Initiates a fight with a slime.
- fightBeast(): Initiates a fight with a fanged beast.
- fightDragon(): Initiates a fight with the dragon.
- goFight(): Sets up the fight interface.
- attack(): Executes an attack on the monster.
- dodge(): Attempts to dodge the monster's attack.
- defeatMonster(): Rewards the player for defeating a monster.
- lose(): Triggers the game over sequence.
- winGame(): Triggers the victory sequence.
- restart(): Restarts the game.
- easterEgg(): Navigates to the Easter egg game.
- pickTwo(), pickEight(): Number picking options for the Easter egg game.
- pick(guess): Executes the Easter egg number guessing game.
