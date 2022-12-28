<img src="https://github.com/MiguelRobles7/MPY2T1/blob/post-project/logo.png" />

# Moondew Isles

Machine project for CCPROG3 class at De La Salle University.

This Java-based game is a farming simulation game, where the player acts as the sole farmer (and manager) of their own farm.

As the name suggests, the game mechanics are heavily inspired by Stardew Valley. 

**Due to licensing only the executable version is published**

## Requirements
Requires [Java JRE](https://www.java.com/en/download/manual.jsp) 11.0.0 or higher to run.

## Controls

| Action            | Key                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Movement | `WASD` |
| Interact with Tile | `Enter` |
| Continously Interact and Move | `Hold e` |
| Switch to Harvesting Hand | `1` |
| Switch to Hoe | `2` |
| Switch to Seeds | `3` |
| Switch to Watering Can | `4` |
| Switch to Fertilizer | `5` |
| Switch to Pickaxe | `6` |
| Switch to Shovel | `7` |
| Toggle Seed Select | `i` |
| Check for Promotion | `o` |
| Pause Game | `p` |
| End Day | `q or use the bed` |

## Quick Mechanics Overview
#### The Farmer
The farmer carries ObjectCoins, the game's currency, experience, and a farmer type.

#### Farmer Type
The player starts off as a regular farmer. With enough objectcoins and experience, the player can opt to achieve the next farmer type. With each new farmer type comes different bonuses.
Each level of promotion rewards the player with the following: 
- Bonus Crop Yield
- Bonus Coin Yield
- Bonus Experience Yield
- Seed Cost Discount

#### The Plot
The farmer has a 10 x 5 plot that they can interact with. Generally the player would want to plow and plant crops in the tiles on the plot.

#### Rocks
There are rocks scattered in the plot where the farmer can farm. The farmer cannot interact with a tile that has a rock. To remove a rock the player must use the pickaxe to mine it for 50 ObjectCoins.

#### Crops
There are different crops with different needs and yields. Check the seed menu to find out all the different type of crops and their yields.

#### Trees
Tree crops are somewhat special. They can only be planted when in non-edge tiles and with no tiles with crops, withered crops, or rocks all around them. 
After a tree is planted however, other crops can be planted around them.  

#### Harvesting Bonuses
- Watering a crop until its maximum water bonuses increases a crop's overall value.
- Each application of fertilizer till its maximum increases a crop's overall value.
- A crop with a type of flower has a 1.1 bonus overall yield.
- A player's farmer type can also influence the overall bonus yield. 

#### Withering Crops
Crops can wither if their minimum water and fertilizer day-to-day are not met. Withered crops cannot be interacted with.

#### Shoveling 
The player may use the shovel to remove crops and withered crops for a small price of 7 objectcoins. 
Using the shovel on any other tile reduces the player's objectcoins but does nothing else. 

#### Game End Conditions
The player will reach a game over if any of the following happens: 
- All tiles in the plot turn withered.
- The player runs out of money to plant a crop. 
- The day ends with the player not having any crops planted. 
The game can theoretically go on forever. 



## Screenshots

![App Screenshot](https://github.com/MiguelRobles7/Moondew-Isles/blob/main/screenshots/House.png)
![App Screenshot](https://github.com/MiguelRobles7/Moondew-Isles/blob/main/screenshots/Plot.png)
![App Screenshot](https://github.com/MiguelRobles7/Moondew-Isles/blob/main/screenshots/Animals.png)


## Acknowledgements

 - [Cup Nooble for their Sprites](https://cupnooble.itch.io/)
 - [Ryi Snow's Java Tutorials](https://www.youtube.com/@RyiSnow)
 - [BGM by nojisuma](https://pixabay.com/music/pulses-a-bird-10226/)


## Developers

- [@MiguelRobles7](https://github.com/MiguelRobles7)
- [@nzwh](https://github.com/nzwh)