# Stabilization in hierarchical multi-agent games against nature
##### Emilia Rosenqvist and Sara Videfors
To not clog our thesis with all the results of our experiments, they are gathered here. A link to the thesis will be added here later on!

## All hierarchical version outputs
The result of all the hierarchical versions of all games can be found in this repository under /results. To simplify reading, all states are defined as a number regardless of if it was a number in the original game description or not. Each player is listed in order, so the left number represents Player 0's knowledge and the right number represents Player 1's. When a "-" is displayed, it means the player knows the difference between all states of the game. Any combination of numbers means the player does not see the difference between the those listed states, so for example "[0, 1, 2]" means that the player cannot differentiate the states 0 to 2, but if there are more states it can identify them. Combinations of lists like "[0, 1][2, 3]" means the player cannot see the difference between state 0 and 1, and state 2 and 3, but it could differentiate between state 1 and 2 for example.

The log output shows which iteration it is (with G0K as the original game) and how many nodes it contains. It also shows if the graph is isomorphic to the previous iteration, as well as if the observations are the same. The Iso type is the type of stabilizations we have; 0 is for non-stabilized iterations, 1 is for iterations that stabilize with regards to isomorphy of the graph, and 2 is for iterations that stabilize both with regards to observations and isomorphy of the graph.

## Game graphs
Some game graphs were too big and complicated to fit into our document, so they can be found in this repository under /graphs.
