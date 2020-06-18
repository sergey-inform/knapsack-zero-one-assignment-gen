# knapsack-zero-one-assignment-gen
Generate non trivial variants for [knapsack zero-one](https://en.wikipedia.org/wiki/Knapsack_problem) problem assignment.

## Assignment example
You have some ideas on which research topics to include in your school project. You certainly will not have time to implement all the ideas. You consulted with a teacher, and for each idea, he assessed the complexity of its implementation, as well as its academic value on a five-point scale (shown in the table).

In total, you are not ready to spend more than 1 hour per day on the project, so in two weeks you have only 14 hours. What ideas are worth the time to maximize the total academic value of the project?


|Idea | Hours | Value | 
|:-- | -- | -- | 
| A | 5 | 3 | 
| B | 10 | 5 | 
| C | 6 | 4 | 
| D | 5 | 3 | 

Encoded: ```[ 5, 10, 6, 5] 	 (3, 5, 4, 3)```

Solution: ```#1 #3 (A and C)```

## Running
``` 
python3 -m venv env
. env/bin/activate
pip3 install  jupyter --upgrade
pip3 install numpy
jupyter-notebook  Knapsack\ 0-1\ solver.ipynb 
```
