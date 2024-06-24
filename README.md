<h1>Intelligent Systems</h1>

Project 01: "Search Algorithms"

Kennia Jackeline Sánchez Castillo​ A00517129 <br>
Prof. Luis Ricardo Peña Llamas Monterrey, Nuevo León April 02, 2024
<hr>

Objective
Apply the different algorithms covered in the Search Algorithms classes: <br>
➔ Uninformed Search. <br>
➔ Informed Search.

<hr>

<i>Problem 1:</i> <strong>Breadth First Search</strong> <br>
Implement the breadth-first search (BFS) algorithm in the breadthFirstSearch function in search.py. Again, write a graph search algorithm that avoids expanding any already visited states. Test your code the same way you did for depth-first search.
 
<code>python3 pacman.py -l mediumMaze -p SearchAgent -a fn=bfs </code> <br>
<code>python3 pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z </code>

<i>Problem 2:</i> <strong>A* search</strong> <br>
Implement A* graph search in the empty function aStarSearch in search.py. A* takes a heuristic function as an argument. Heuristics take two arguments: a state in the search problem (the main argument), and the problem itself (for reference information). The nullHeuristic heuristic function in search.py is a trivial example.
 
<code>python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic</code><br>
