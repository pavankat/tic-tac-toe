Made an unbeatable Tic Tac Toe game with some typography to make it look nice.

I broke a lot of what I did into functions and used arrays where appropriate. 

The AI loops through a multidimensional array of winning combinations, and prevents them from happening when 2/3 of the combination is filled.

When none of the combinations are in danger of being filled, the computer will check if the 6th and and 8th spots are taken by the player and if the last spot isn't taken, the computer will take the last spot.

If a set of diagonal corners are taken by the player, then the computer takes a non-corner/non-center space.

If that's not the case, then the computer will try to take the center of the board. 

If the center is filled already, then the computer will take the first corner position. 

If all the corners are taken then the computer will take the first empty square.

