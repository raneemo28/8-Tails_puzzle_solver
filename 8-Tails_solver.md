a C# implementation of classic 8-Tails solver using A* algorithem taking sum of manhatten distance between the current place of the tail and its targeted place as a heuristic 
considering that the user may enter invalid input.
input :a path to a text file include the starting state of the puzzle eg:  iput.txt
example of what the file (input.txt) should contains : 
235
7 4
186
output : starting state, goal state ,a series of moves that the user should implement on the space to win the game , total number of moves 
eg_1 :
Starting Puzzle State:
1 2 3
4 5 6
7   8

Goal State:
1 2 3
4 5 6
7 8

Solving...

Solution Found!
Path:
- Right
Total moves: 1

eg_2 :
Starting Puzzle State:
8 2 3
4 1 6
7   5

Goal State:
1 2 3
4 5 6
7 8

Solving...

Solution Found!
Path:
- Right
- Up
- Up
- Left
- Down
- Down
- Left
- Up
- Up
- Right
- Right
- Down
- Left
- Left
- Down
- Right
- Up
- Right
- Down
Total moves: 19
