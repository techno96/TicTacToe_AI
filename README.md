# TicTacToe_AI
Python implementation for AI player playing TicTacToe based off Markov Decision Process (MDP)

* AI plays against a random opponent which picks uniformly off the empty spots.
* The game is modeled as an MDP, with AI taking optimal actions.
* **Discount factor** γ = 0.9
* **Reward function** : For any game state s that is not terminal (i.e., no winner and there is still some
empty spot), R(s) = 1. For any game state s that you are the winner, R(s) = 10, and if you are the loser,
then R(s) = −10. If it is a draw state (all spots are occupied and there is no winner), then R(s) = 0. 
