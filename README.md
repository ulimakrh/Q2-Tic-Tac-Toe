# Quiz 2 DAA : Tic Tac Toe

Ulima Kaltsum RH - 5025211232
DAA E

Tic tac toe is a two-player game that takes turns marking the spaces available in a three-by-three grid with ‘X’ or ‘O’. The first player who succeeds in marking three of their symbols in the grid by horizontal, vertical, and diagonal row will win the game. If the condition is not met, the game will end in a draw. There are no specific rules for deciding which player will go first, but usually, the first player goes by the symbol of ‘X’. There is only one rule in playing tic tac toe, which is both players can’t mark their symbol in a place where it has been marked before.
The instruction for playing tic-tac-toe in our program:
1.	Decide which player will be going first
2.	The first player will mark their symbol by choosing the appropriate number
3.	The second player will continue by marking their symbol
4.	Repeat the process until either player win the game
5.	(NOTE: Either player can’t choose the same place)

The theory I used in my program is DFS or Depth First Search. DFS is a method for traversing or searching a specific value in a tree. The algorithm starts from the root node and it will keep on traversing until it reaches the expected results. There will be two categories that DFS can reach, which are visited or not visited. The purpose of this algorithm is to mark each location on whether they have been visited or not. For the operation to work, there are several steps that need to be done, which start by putting any one of the graph’s vertices (location of X or O in the game) on top of the stack. Then, take the top item of the stack as visited. After that, repeat the process until there are no spaces available in the tic tac toe or until either player 1 or player 2 have won the game. 
