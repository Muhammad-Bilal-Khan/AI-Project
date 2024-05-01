# AI-Project

Problem Statement:
S represents the start state.
G(k) represent the goal states where k could be from 0 to 3 in the environment.
A(i) represent the ith number of Agent in the environment. Our agent will be Agent(0).
X represents barriers that the agent cannot pass through.
O represents potholes that deduct points when encountered. The number inside the bracket represents the deduction.
C represents coins with varying values that add to the total points of the agent. The number inside the bracket represents the coin value.
E.g.

Coins (C):
= C(10)
= C(5)

Potholes (O):
= O(-6)
= O(-90)

Your AI agent has to go through the simulated environment and reach any one of the goals. It will keep track of the complexity of the search (complexity as discussed in the course).

Whenever the program starts, it will start with a random grid of m x n where m,n will be supplied by the user as input. User will also be prompted to enter starting position p1,p2 inside the grid and the number of goals (k). The grid will then be populated randomly with coins, potholes and goals. The user will be prompted to use one or more of the algorithms to search for the goal. Once the task is complete, the output will show the complexities of each of the algorithm used and the evaluation function. For now, the evaluation function is simply the addition of rewards and penalties of encountering coins and obstacles.

Project Update 1:
Incorporate CSP into your projects. Formulate the problem into a CSP problem. Provide a comparison of status space reduction performance improvement after solving the CSP.
