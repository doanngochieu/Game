# CARROTS_CLASH!
a 2-player 2D game created in SDL for Windows. 

## How to play
  - Player 1 controls: Arrow keys
  - Player 2 controls: WASD keys

| Entity        | Effects                        |
| ------------- | ------------------------------ |
| Rose          | Lose game                      |![Ingame](Textures/flower01.png)
| Carrot        | Score 1 Point                  |
|               | Increase enemy speed           |
| Green flower  | Get poisoned                   |
| Blue flower   | Reduce player speed            |
|               | Increase life left from poison |
| Pink flower   | Invert player controls for 2s  |
|               | Invert enemy controls for 4s   |
| Yellow flower | Lose 3 Point                   |
|               | Increase player speed greatly  |
|`Poison effect`| Lose game in Poison time (10s) |

### How to win?
- Avoid roses while trying to collect as many as possible carrots (Collecting carrots increases enemy speed, which makes it harder for them to avoid roses)
- In case you get poisoned, catch the enemy player to win the game. Or lose, if poison time hits zero.
- In the case where one rabbit has a higher score, it can eat the other rabbit.

---

## About 
 My game is based on the theme of rabbits eating carrots. There are many ways to play this game, such as just eating carrots to score points or having the rabbit with a higher score chase the other rabbit.
 
### How did I do it?
I've mostly used <a href="http://lazyfoo.net/SDL_tutorials/">LazyFoo</a> SDL tutorials to understand how SDL library works. Later I found a helpful <a href="http://staniks.github.io/">Staniks</a> game tutorial where he implements a small coin game.

The game is not very optimized and the code is kinda messy. I also certainly lacks comments. It was one of my first projects, but I've learned much from it and I will strive to improve in the future.
 
---

##### Special thanks to:
 - <a href="http://sol-myr.deviantart.com/">Mirna</a> - The famous graphic designer. Did some coding also.
 - <a href="https://github.com/athnix/">athnix</a> - My dear helpful fix bugger and tester. Bad gaming skills tho. (specially at CS:GO... jk.)
 - <a href="https://github.com/sklavko/">sklavko</a> - Tester with some crazy gaming abilities.

## Link demo
https://drive.google.com/drive/folders/1GMdsAy_XwyN3rz9Ej9LKjUwqRSiC6fR1?usp=drive_link
