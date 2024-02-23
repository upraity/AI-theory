# HILL CLIMBING METHOD  

- Hill climbing algorithm is a local search algorithm which continuously moves in the direction of increasing elevation/ value  to find the peak of the mountain or best solution to the problem. It terminates when it reaches a peak value where no neighbour has a higher value.
- Hill climbing algorithm is a technique which is used for optimising the mathematical problem. One of the widely discussed examples of Hill climbing algorithm is TRAVELING - SALESMAN  problem in which we need to minimize the distance travelled by the salesman. 
- A node of hill climbing algorithm has two components which are state and value.
- Hill climbing is mostly used when a good heuristic is available .
- It always moves in a single direction.
- In this algorithm, we don’t need to maintain and handle the search tree and graph as it only keeps a single current state.
 
## Features of Hill Climbing Method

1. *Generate and test variant* :- Hill climbing is the variant of generate and test method. The generate and test method produce feedback which helps to decide which direction to move in the search space.
2. *Greedy approach* :- Hill climbing algorithm search moves in the direction which optimize the cost.
3. *No Backtracking* :- It does not backtrack the search space, as it does not go to the previous state.

## Types of Hill climbing

1. Simple Hill Climbing.  
2. Steepest - Ascent Hill Climbing.  
3. Stochastic Hill Climbing.  

# Algorithm.  

Step1: - Evaluate the initial state, if it is goal state then return success and stop.  
Step2: - Loop until a solution is found or there is no new operator left to apply.  
Step3: - Select and apply an operator to the current state.  
Step4: - Check new state:  
     (a) If it is goal state, then return success and quit.  
     (b) Else if it is better than the current state then assign new state as a current state.  
     (c) Else if not better than the current state, then return to Step -2. 
Step5: - Exit.   


## Problems in Hill Climbing.

Hill Climbing cannot reach the optimal / best state( global maximum) if it enters in any of the following state:  

1. Local Maximum: At a local maximum all neighbouring states have a value that is worse than the current state.Since hill climbing uses a greedy approach, it will not move to the worse state and terminate itself. The process will end even though a better solution may exist.
2. Plateau : On the plateau, all neighbours have the same value. Hence, it is not possible to select the best direction. 
3. Ridge: Any point on a ridge can look like a peak because movement in all possible directions is downward. Hence the algorithm stops when it reaches this state.

## Advantages of Hill Climbing Method
- It is simple algorithm that is easy to understand and important.  
- It can be used in a wide variety of optimization problems, including those with a large search space and complex constraints.  
- Hill climbing is often very efficient in finding local optima(maxima), making it a good choice for problems where a good solution is needed quickly.  

## Disadvantages of Hill Climbing Method
- Hill climbing can get stuck in local optima, meaning that it may not find the global optimum of the problem.
- Hill climbing does not explore the search space where very thoroughly, which can limit its ability to find better solution.

> By: _Lucky Kulshrestha_
