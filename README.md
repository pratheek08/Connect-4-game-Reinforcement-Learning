# Connect-4-game-Reinforcement-Learning
I have developed an intelligent game-playing bot for the Connect 4 in a Line game using Reinforcement Learning (RL)  The RL agent is capable of making optimal moves, to play strategically, making decisions to win or prevent the opponent from winning.

## Files
`connect_four.py:` The code for the connect four game mechanics, including managing the board state, updating it with a move input, and checking for win conditions (ie, if the current board states has a vertical, horizontal, or diagonal four in a row, as well as if the board state is a tie)

`q_learning.py:` The code for learning the Q function for the Connect Four AI. Contains the code for generating episodes with self-play. Also contains code for the main training loop (ie, implementing the MC-TS and Q-Learning algorithm) and testing the trained Connect Four AI.

`run.py:` Used to actually start the RL experiments.

`Plots.py:` A jupyter notebook used to plot the results.

## Required packages and libraries 
We require matplotlib, numpy, pandas, and tqdm python packages.

## Output
<img width="316" alt="image" src="https://github.com/pratheek08/Connect-4-game-Reinforcement-Learning/assets/83898956/f34ba00b-be51-4758-b686-0d842a436cf9">
