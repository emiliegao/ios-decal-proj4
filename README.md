# Click War

## Authors
* Kevin Lu
* Emilie Gao

## Purpose
Click War is a fun interactive game in which players defeat monsters by tapping on their screen to deal damage!

## Features
* The goal of the game is to get points from defeating enemies.
* Players deal damage by tapping on the screen.
* Players fight enemies at the Battlegrounds.
* Players can buy weapon upgrades and pets that will automatically deal damage.

## Control Flow
* Players are initially presented with a splash screen, which leads them to a click-through instruction view on first start up. This tutorial will teach them how to play the game (click to attack, buy stuff from store, buy pets and what pets do, etc).
* Upon finishing the tutorial, players will be presented the Battlegrounds View where they will fight a beginner enemy. 
* Players then can continue to fight at the battlegrounds, which has an endless stream of enemies.
* Players will keep on defeating enemies and accumulating points.
* Players can tap the shop button to go to the Shop to buy upgrades.
* Players can also tap the pets button to go to the Pet Shop to buy pets.
* After shopping, players can return to the Battle View where they will continue to fight enemies.
* If this project needs more complexity, can add random events (like boss fights or random chest/loot drop). Can also add more things that can be bought like houses or something.

## Implementation

### Model
* Player
* Enemy
* Pet
* Battlegrounds

### View
* TutorialView
* BattlegroundsView
* WeaponshopView
* PetshopView
* StatsView

### Controller
* TutorialViewController
* BattlegroundsViewController
* WeaponshopViewController
* PetshopViewController
* StatsViewController