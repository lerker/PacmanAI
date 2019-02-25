# PacmanAI
Berkeley implementation of Pacman AI adapted by Nelson Ponzoni only for teaching propourses


__Files you'll edit:__
search.py: Where all of your search algorithms will reside.
searchAgents.py: Where all of your search-based agents will reside.
__Files you might want to look at:__
pacman.py: The main file that runs Pacman games. This file describes a Pacman GameState type, which you use in this project.
game.py: The logic behind how the Pacman world works. This file describes several supporting types like AgentState, Agent, Direction, and Grid.
util.py: Useful data structures for implementing search algorithms.


# [The Pac-Man Projects](http://inst.eecs.berkeley.edu/~cs188/pacman/project_overview.html)

![pacman_game](pacman_game.gif)

The Pac-Man projects were developed for UC Berkeley's introductory artificial intelligence course, CS 188. They apply an array of AI techniques to playing Pac-Man. However, these projects don't focus on building AI for video games. Instead, they teach foundational AI concepts, such as informed state-space search, probabilistic inference, and reinforcement learning. These concepts underly real-world application areas such as natural language processing, computer vision, and robotics.


## Projects

* P1 - [Search](http://inst.eecs.berkeley.edu/~cs188/pacman/search.html): implement depth-first, breadth-first, uniform cost, and A* search algorithms. These algorithms are used to solve navigation and traveling salesman problems in the Pacman world.

* P2 - [Multi-Agent Search](http://inst.eecs.berkeley.edu/~cs188/pacman/multiagent.html): implement multiagent minimax and expectimax algorithms, as well as designing evaluation functions.

* P3 - [Reinforcement Learning](http://inst.eecs.berkeley.edu/~cs188/pacman/reinforcement.html): implement model-based and model-free reinforcement learning algorithms, applied to the AIMA textbook's Gridworld, Pacman, and a simulated crawling robot.

* P4 - [Ghostbusters](http://inst.eecs.berkeley.edu/~cs188/pacman/tracking.html): implement exact inference using the forward algorithm and approximate inference via particle filters.   

* P5 - [Classification](http://inst.eecs.berkeley.edu/~cs188/pacman/classification.html): implement standard machine learning classification algorithms using Naive Bayes, Perceptron, and MIRA models to classify digits then extend this by implementing a behavioral cloning Pacman agent.

* P6 - [Contest: Pacman Capture the Flag](http://inst.eecs.berkeley.edu/~cs188/pacman/contest.html): create strategies for a team of two agents to play a multi-player capture-the-flag variant of Pacman.



# P1 - [Search](http://inst.eecs.berkeley.edu/~cs188/pacman/search.html)

![maze](maze.png)

All those colored walls, mazes give Pacman the blues, so teach him to search. Implement depth-first, breadth-first, uniform cost, and A* search algorithms. These algorithms are used to solve navigation and traveling salesman problems in the Pacman world.

`search.py` - the search algorithms  
`searchAgents.py` -	the search-based agents  
`pacman.py`	- the main file that runs Pacman games  
`game.py` - the logic behind how the Pacman world works  
`util.py` - useful data structures for implementing search algorithms  


* Q1: Depth First Search (`search.py` - `depthFirstSearch`)
* Q2: Breadth First Search (`search.py` - `breadthFirstSearch`)
* Q3: Uniform Cost Search (`search.py` - `uniformCostSearch`)
* Q4: A* Search (`search.py` - `aStarSearch`)
* Q5: Corners Problem: Representation (`searchAgents.py` - `CornersProblem`)
* Q6: Corners Problem: Heuristic (`searchAgents.py` - `cornersHeuristic`)
* Q7: Eating All The Dots: Heuristic (`searchAgents.py` - `FoodSearchProblem`)
* Q8: Suboptimal Search (`searchAgents.py` - `findPathToClosestDot`)