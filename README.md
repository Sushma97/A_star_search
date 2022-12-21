# A_star_search

https://courses.grainger.illinois.edu/cs440/fa2022/MPs/mp2/instructions.html

Implementing the A* search algorithm for solving 3 different search problems - EightPuzzle, WordLadder, and GridSearch. Single implementation of the algorithm will work for all 3 problems, by properly instantiating an AbstractState class for each of them. We will see both the power of A* as an algorithm that applies to arbitrary discrete state spaces, and the power of heuristics to speed up search.

Run best_first_search on all WordLadder problems:

```python3 main.py --problem_type=WordLadder```

Run best_first_search on EightPuzzle problems (all puzzles with puzzle_len=N can be solved in N steps):

```python3 main.py --problem_type=EightPuzzle --puzzle_len=5```

Run best_first_search on Single grid search problem: 

```python3 main.py --problem_type=GridSingle --maze_file=[path_to_maze_file in data/mazes/grid_single]```

Run Multi Goal Grid Search:

```python3 main.py --problem_type=GridMulti --maze_file=[path_to_maze_file in data/mazes/grid_multi]```

## I hereby state that I shall not be held responsible for any misuse of my work or any academic integrity violations. ##
## DO NOT COPY. Only for reference ##
