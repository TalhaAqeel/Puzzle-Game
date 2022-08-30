########     Basics of Game     #########
Click on the tile so that it would move.
The underlying textbox is to put a url of image



######   Some Basics of Code line-by-line######
In the helper.js file all, the program/game logic is deployed.
The style and formatting of all game is made in index.css file.
In the Line 8 of Board.js file, the code is written to keep track of each tile so that after juggling/mixing the tiles the correct order should be maintained so that after placing the tiles in correct order the game should end.
In Line 37 and 38, the size of tile is specified based upon size of board and the uppercase letters in these lines are imported from constants.js file.
In the constants.js file the size of board and number of tiles are specified.
In the Board.js file and in lines 40-43 a style object is created which used in line 48 and ahead.
In the Board.js file and from line 51 onward each tile is mapped then index, width and height was passed on.
In the Line 8 of Tile.js file the props are declared ,props are the read-only components which stores the value of tag or something.
From Line 5 to 13 in helper.js file the code is taken from a similar project, but it was so much neat and complete that I had to add it so credited them as well. The same code is written so that it is solvable and if not then should be randomized again.
In the Line 12 of helper.js file the round function is called so that to strictly round-off to nearest whole-number 1(because of ===).
As per the requirement in case of win condition a function is specified in the helper.js file between lines 15 to 20.
In the lines 29 to 35 in helper.js file it also assigns the index number to a object.
In the line 37 in helper.js file, the visual function is declared to obtain the exact position of tile as the tile is positioned absolute.
In the line 51 in helper.js file, the function is declared to check either the random tiles are solvable or not.
In the Board.js file and from line 51 onward function is declared to shuffle the tiles after clicking on start game.
In the App.js file from Line 6 to 19, textbox is inserted in which when entered an url address the image shows on whole tiles.
