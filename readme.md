# Maximum profit by buying and selling a share at most twice


## Problem Statement

In daily share trading, a buyer buys shares in the morning and sells them on the same day. If 
the trader is allowed to make at most 2 transactions in a day, whereas the second transaction 
can only start after the first one is complete (Buy->sell->Buy->sell). Given stock prices 
throughout the day, find out the maximum profit that a share trader could have made. 

## DESIGN TECHNIQUE – DYNAMIC PROGRAMMING

Dynamic programming is a technique that breaks the problems into sub-problems, and saves 
the result for future purposes so that we do not need to compute the result again. The 
subproblems are optimized to optimize the overall solution is known as optimal substructure 
property. The main use of dynamic programming is to solve optimization problems. Here, 
optimization problems mean that when we are trying to find out the minimum or the 
maximum solution of a problem. The dynamic programming guarantees to find the optimal 
solution of a problem if the solution exists. 
The definition of dynamic programming says that it is a technique for solving a complex 
problem by first breaking into a collection of simpler subproblems, solving each subproblem 
just once, and then storing their solutions to avoid repetitive computations. 
