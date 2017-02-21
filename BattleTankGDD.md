# Battle Tank GDD

## Concept

Battle Tank will be a one on one tank battle game. The battle will take place on a generated piece of terrain with hills, divots etc. Each tank will have a set amount of ammunition and a damage indicator. A successful hit will increase the damage on the hit tank. The battle ends when one tank is incapcitated. Players will have the option of playing against a computer controlled tank or against another local player.

## Rules
* One on one tank battle
* Each tank has the same amount of ammo and health
  * In the future, could have different kinds of ammo that cause different amounts of damage

## Requirements
* Generated terrain or a programmatic means of generating terrain
* A tank mesh and skeleton
  * Start with a primitive setup
* Tank textures
* Menu system for setting game options
* Projectile motion mechanics for cannon shots
* "Tank-like" control scheme where the turret can move independently of the tank body but is still restricted where it cannot go through the tank body
* Sound effects for:
  * Cannon firing
  * Explosions
  * Tank treads moving, engine
  * Cannon moving
  * Background music

## Iterative Cycle Development
* Build world first
* Build the tank (primitive at first)
* Build the controls for the tank
* Build the second player logic
* Build the user interface
* Repeat and clean up each step as long as necessary until the game is polished and fun
