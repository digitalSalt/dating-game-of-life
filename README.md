Modified Conway's Game of Life with JavaScript and Canvas
================================================

The Dating Game of Life is a variation of Conway's GoL with an aspect of relationships. 
The rules to the game are: 
* Every new pixel has an equal chance of being blue(male) or red(female)
* A pixel dies from overcrowding (>=4 neighbours) or loneliness( < 2 neighbours) as in the original GoL
* If am empty square has 2 or 3 neighbours which include a male and female, a new pixel is "born" with 50% likelihood

View the live demo at https://digitalsalt.github.io/dating-game-of-life/.
(Initial conditions are randomly generated, with each square having a 10% chance of being a live pixel)

* Press `<space>` to pause/unpause the simulation.
* Press `<n>` to step the simulation while paused.
* Press `<r>` to reset the simulation.
