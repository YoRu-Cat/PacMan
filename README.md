Hello There Fellas!
This game is Completely Customizeable. You can create your own levels, increase speed of enemy and increase moving comlexity of the enemies just by changing these simple values:
1 - If you want to Customize the TileMap : Go to the **src** Folder and open **TileMap.js** File. You'll find a 2D array named as **map**.
 In the map the numbers identify as follow: 
 // 0 - dots
 // 1 - walls
 // 4 - PacMan
 // 5 - EmptyS Space (the space left after pacman eats the dot)
 // 6 - enemies
 // 7 - power dots (flashing dots)

 Default one is : 
  map = [
    [1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1],
    [1, 0, 0, 0, 0, 0, 0, 0, 0, 6, 0, 7, 1],
    [1, 0, 1, 1, 1, 1, 1, 1, 1, 0, 1, 0, 1],
    [1, 0, 1, 0, 0, 0, 0, 0, 0, 0, 1, 0, 1],
    [1, 0, 1, 0, 1, 1, 1, 1, 1, 1, 1, 0, 1],
    [1, 0, 6, 7, 0, 0, 0, 0, 0, 0, 0, 0, 1],
    [1, 0, 1, 0, 1, 1, 1, 1, 0, 1, 1, 1, 1],
    [1, 0, 1, 0, 1, 0, 4, 0, 0, 0, 1, 7, 1],
    [1, 6, 1, 0, 0, 0, 1, 0, 1, 0, 0, 0, 1],
    [1, 0, 0, 0, 1, 0, 1, 0, 0, 0, 1, 0, 1],
    [1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1],
  ];
2 - If you want to increase move speed : Go to the **src** Folder and open **Game.js** File. You'll find a variable named as **velocity**. Increase or decrease it as you like 😉.
 Default one is : 
 const velocity = 2;
3 - If you want to increase the Complexity of the enemies movement : Go to the **src** Folder and open **Enemy.js** File. In the **constructor** You'll find this line :
 this.directionTimerDefault = this.#random(1, 3);
 // 1 - min value
 // 3 - max value
 Change these values accordingly. 
ENJOY!!😊
