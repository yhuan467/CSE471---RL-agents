# CSE471---RL-agents
Implemented 5 reinforcement learning algorithms (Value Iteration, Q-Learning, Approximate Q-Learning, SARSA, Deep Q-Network) in Python. Trained agents across Gridworld, Crawler, and Pacman environments.  Achieving 100% win rate over 100 eval games.

# Reinforcement Learning Agents

Implemented core reinforcement learning algorithms in Python across three 
environments: Gridworld, Crawler, and Pacman.

## Algorithms Implemented

| Algorithm | File |
|---|---|
| Value Iteration | `valueIterationAgents.py` |
| Q-Learning | `qlearningAgents.py` |
| Approximate Q-Learning | `qlearningAgents.py` |
| MDP Policy Analysis | `analysis.py` |

## Key Result

Trained a Pacman agent over 2,000 episodes — achieved **100% win rate** 
across 100 evaluation games with an average score above 500.

## How to Run

**Requirements:** Python 3.x (no additional packages needed)

**Value Iteration on Gridworld:**

python gridworld.py -a value -i 100

**Q-Learning on Gridworld:**
python gridworld.py -a q -k 100

**Train Pacman with Q-Learning:**
python pacman.py -p PacmanQAgent -x 2000 -n 2010 -l smallGrid

**Run autograder:**
python autograder.py

## Files I Wrote

- `valueIterationAgents.py` — Value Iteration agent
- `qlearningAgents.py` — Q-Learning and Approximate Q-Learning agents  
- `analysis.py` — MDP parameter analysis

All other files are part of the UC Berkeley CS188 course framework.
