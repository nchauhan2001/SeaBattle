# Jacksonville State University
# CS232 – Computer Programming II: Fall 2022 
# Project #2: Sea Battle II 

Sea Battle II was the last project of this course which was done in a group of 3 students including me.
Nidhi Chauhan; Sunit Sharma; Dalton Estes

The purpose of this project was to get the enough of practice using GUI programming and the Model/View/Controller design pattern to implement a game called "Sea Battle II". 
This is a two-player version of the popular strategy game, Battleship.

This game is played on four 10x10 grids, two for each player.  Each player is assigned: a primary grid, a tracking grid, and a fleet of nine ships, deployed at random within their respective primary grids. 
Depending on their size, the ships occupy two to five squares each, and they were deployed in such a way that all of the ships fit within the bounds of the grid without overlapping.

The players take turns firing shots at target squares within their opponent's primary grid, one shot per turn.  Both hits and misses are recorded within the player's tracking grid, and in the opponent's primary grid.  
The object of the game is to sink every ship in the opponent's fleet; to sink a ship, it is necessary to hit every square that it occupies.  The first player to sink every ship in their opponent's fleet is the winner.

At the start of a game, the "Sea Battle II" program is launched and between turns, the game will "hide" the grids, so that neither player's primary grid is exposed to their opponent.
The program starts by creating a primary grid and tracking grid for each player and Player 1 then gets the first turn.

During each of the player's turn, the attacking player selects the coordinates of a target square by clicking it within the tracking grid.  The target square is then marked in the tracking grid of the attacking player, and on the primary grid of the opponent. 
The program then indicates whether the shot was a "miss", a "hit", or a "sink".  The fleet counts of both players are displayed at the bottom of the window, and are kept up to date as the game progresses.

When player's turn ends, the players reverse roles on the next turn starts, and continue taking shots until all of the ships in one player's fleet have been sunk.

The complement of ships is as follows in each player's fleet:

Quantity     Ship Type     Squares

   1      Aircraft Carrier    5
   1        Battleship        4
   2        Destroyer         3
   2        Submarine         3
   3        Patrol Boat       2
  
As a result, the squares occupied by each ship are indicated by icons within the primary grid.  
As the players take their shots, the target squares are marked with a "splash icon" if the shot was a miss, or an "explosion icon" if the shot resulted in a hit or a sink.  Corresponding marks are also made in each player's tracking grid, so that the player can keep track of which squares they have already fired upon. 

This project was a great opportunity for me to learn how to implement this 'Battleship' game using Java's advanced tool GUI & Model/View/Controller.
Thank you so much!
