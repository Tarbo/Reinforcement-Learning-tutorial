# Reinforcement-Learning-tutorial: Contextual Bandit Application in E-commerce

This repository contains three Jupyter notebooks, each implementing a different algorithm for solving the contextual bandit problem. The algorithms implemented are Thompson Sampling, Upper Confidence Bound (UCB), and Epsilon-Greedy.

## Files

1. `src/thompson_sampling_c_bandit.ipynb`: This notebook implements the Thompson Sampling algorithm for a contextual bandit problem. Thompson Sampling balances exploration and exploitation by maintaining a probability distribution over the expected reward of each action and selecting actions according to these distributions.

2. `src/ucb_c_bandit.ipynb`: This notebook implements the Upper Confidence Bound (UCB) algorithm for a contextual bandit problem. UCB balances exploration and exploitation by selecting actions that have the highest upper confidence bounds on the expected reward.

3. `src/epsilon_greedy_c_bandit.ipynb`: This notebook implements the Epsilon-Greedy algorithm for a contextual bandit problem. Epsilon-Greedy balances exploration and exploitation by selecting the best action most of the time, but selecting a random action with a small probability (epsilon).

## Usage

To use these notebooks, you will need a Python environment with the following packages installed:

- numpy
- pandas
- matplotlib
- seaborn

You can run each notebook in a Jupyter environment. The notebooks include code to train the agents and visualize the results. You can adjust the number of states, actions, and episodes to fit your specific problem.

## License

This project is licensed under the terms of the MIT license.
