# Woborms - Sapienza Interactive Graphics project
This project is an attempt to create a game inspired by the famous series of games **Worms**.\
Worms is a turn-based game where teams of worms in a 2D map try to shoot at each other, after deciding the angle of aim and the "power" of the shot (thus creating a trajectory for the projectile). The last team to remain alive wins.\
Some Worms games were created in a 3D setting (exclusively 3D levels instead of the classical 2D), and in particular I will take insipration from one of them, *Worms 4: Mayhem*.\
\
The project uses **Three.js** and **Cannon.js**.

## How to play
**IF THE GAME DOESN'T WORK WELL OR IS TOO SLOW, TRY TO OPEN IT IN ANOTHER BROWSER**\
You can play the game [here](https://sapienzainteractivegraphicscourse.github.io/final-project-stesb24/).
- Use **WASD** or **arrow keys** to move around or take the aim when in first person view;
- press **E** once to look from above, press again to go back to third person view;
- press **Q** once for first person camera, press again to switch back to third person view;
- hold **spacebar** to charge up the shot (the more you press, the further the bullet will go); release it to shoot.
After shooting, your turn ends and you can't act anymore. Some time after the projectile hits something or falls off the map, the next turn starts.\
More in-depth instructions can be found in the game.

### Known issues
Sometimes the collisions between bullets and some bodies are not perfect, but I believe this is a problem of Cannon.js (I checked with the Cannon debugger and the objects' hitboxes are defined correctly). Anyway, this problem doesn't really negatively affect the gameplay.
