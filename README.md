#  Genetic-Algorithm
## INTRODUCTION
#### A demonstration of Genetic Algorithm using a C-Program
#### Genetic Algorithm finds its application in a various fields like,	Robotics, Engineering Design, Hardware Evolution, Optimization of Routes, Biomimetic Invention, Computer Gaming and many more.
#### Ours demonstration visualises the evolution of a randomly spawned generation of a hundred organisms having poor fitness & wide diversity converging to a generation having very high fitness & wide diversity. Its demonstrates how the better characteristics of the individuals are carried to next generations and the new generation are superior to their ancestors


#### The following outline summarizes how the genetic algorithm works:

##### 1. The algorithm begins by creating a random initial population.
##### 2. The algorithm then creates a sequence of new populations. At each step, the algorithm uses the individuals in the current generation to create the next 	population. To create the new population, the algorithm performs the 	following steps:
		
		###### a. Scores each member of the current population by computing its fitness value. These values are called the raw fitness scores.
		
		###### b. Selects members, called parents, based on their fitness scores.

##### 3. Some of the individuals in the current population that have higher fitness are 	chosen as elite. These elite individuals are passed to the next population.

##### 4. Children are produced by combining the vector entries of a pair of parents, 	the process is called crossover.
##### 5. The current population is replaced with the children to form the next 	generation.
##### 6. The algorithm stops when one of the stopping criteria is met.
