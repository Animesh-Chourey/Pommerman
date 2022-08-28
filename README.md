A modified MCTS agent has been implemented as part of the assignment.

The selection phase of the MCTS algorithm has been improvised through the process of adding a progressive strategy called progressive bias. The customised agent is designed to play the pommerman game. 

The framework of the game can be found at : [java pommerman](https://github.com/GAIGResearch/java-pommerman)

Below are the instructions for executing this customised agent:
* The package required to run our enhanced MCTS agent (MSCT2) has been integrated into the folder "customised agent". 
* The GameState.java file has been updated and needs to be replaced with the original one present.
* To run our agent(MCTS2), edit the configurations for Run.java and pass the value '7' in place of the indices 4-7. 

For example, the configurations [0 1 1 -1  3 4 5 7] would run a tournament of Free for All between Simple Player, RHEA, MCTS and MCTS2(our customised agent) in full observability.

