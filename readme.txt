Features
-===================-
USAGE:
	nPuzzler.bat <file> <method>

nPuzzler takes two arguments.
The first refers to a text file which contains an n-puzzle of varying sizes.
The second refers to the method that you want to use to solve the puzzle(s) in the above file. See Search Table for a list of valid methods.

File Contents Example
5x3
1 2 3 5 11 6 4 13 9 8 0 12 7 10 14
1 2 3 4 5 6 7 8 9 10 11 12 13 14 0

Search Table
Parameter	|Method Name
----------------+----------
BFS		|Breadth-first Search
GBFS		|Greedy Best-first Search
AS		|A-Star Strategy
DFS		|Depth-First Search
