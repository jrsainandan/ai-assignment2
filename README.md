This project contains a collection of Artificial Intelligence laboratory programs implemented using Python and C. These programs demonstrate important AI concepts such as search algorithms, human verification systems, and intelligent behavior simulation.

The main objective of these programs is to understand how AI techniques can be used for problem solving, decision making, and distinguishing between human users and automated systems.

Turing Test Simulation

This program demonstrates a simplified version of the Turing Test, originally proposed by Alan Turing. In this test, a judge interacts with two participants: one human and one machine. The identities of both participants are hidden from the judge.

The judge communicates with them through text messages and must determine which participant is the human and which one is the machine based on their responses.

Key Concepts

-> Intelligent behavior simulation
-> Human and machine interaction
-> Evaluation of responses
-> Decision making based on conversation

CAPTCHA Authentication System

This program generates a random CAPTCHA consisting of letters and numbers. The user must correctly enter the generated CAPTCHA to verify that they are a human user rather than an automated bot.

If the entered CAPTCHA matches the generated string, the user is authenticated; otherwise, access is denied.

Key Concepts

-> Random string generation
-> Human verification mechanism
-> Basic security implementation
-> Protection against automated bots

Breadth First Search (BFS)

This program implements the Breadth First Search algorithm, which explores nodes level by level until the goal state is reached.

The algorithm uses a queue data structure to store nodes that need to be explored.

Key Concepts

-> Graph searching techniques
-> Queue data structure
-> Level order node exploration
-> Guaranteed shortest path in unweighted graphs

Depth First Search (DFS)

This program demonstrates the Depth First Search algorithm, where the search explores one path as deep as possible before backtracking to explore alternative paths.

The algorithm uses a stack or recursion to manage traversal.

Key Concepts

-> Graph traversal method
-> Stack-based implementation
-> Backtracking strategy
-> Deep exploration of nodes

Depth Limited Search (DLS)

Depth Limited Search is a variation of DFS where the search is restricted to a fixed depth limit. This prevents the algorithm from exploring infinitely deep paths in the search tree.

Key Concepts

-> Controlled depth exploration
-> Recursive search technique
-> Prevents infinite loops
-> Depth restriction in search trees

Iterative Deepening Depth First Search (IDDFS)

This algorithm combines the advantages of Breadth First Search and Depth First Search. It repeatedly performs Depth Limited Search, increasing the depth limit gradually until the goal state is found.

Key Concepts

-> Iterative search process
-> Depth expansion strategy
-> Memory efficient search
-> Combines BFS optimality and DFS space efficiency

Missionaries and Cannibals Problem using BFS

This program solves the Missionaries and Cannibals problem using the Breadth First Search algorithm.

In this problem, three missionaries and three cannibals must cross a river using a boat that can carry at most two people. The constraint is that cannibals must never outnumber missionaries on either side of the river, otherwise the missionaries would be eaten.

The BFS algorithm systematically explores all valid and safe states and finds an optimal sequence of moves that transfers everyone safely to the other side of the river.

Key Concepts

-> State space representation
-> BFS based problem solving
-> Constraint checking
-> Safe state generation
