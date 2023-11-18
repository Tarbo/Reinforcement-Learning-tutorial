# Reinforcement-Learning-tutorial: Contextual Bandit Application in E-commerce

This repository contains two Jupyter notebooks that implement the Thompson Sampling  and Upper Confidence Bound algorithms for a contextual bandit problem.

## Files

1. `thompson_sampling_c_bandit.ipynb`: This notebook implements the Thompson Sampling algorithm for a contextual bandit problem. It defines a `ContextualBandit` class to represent the environment and a `ThompsonSampling` class to represent the agent. The agent selects actions based on the Thompson Sampling algorithm and updates its knowledge based on the rewards it receives. The notebook also includes code to train the agent and visualize the results.

2. `ucb_c_bandit.ipynb`: This notebook implements the Upper Confidence Bound (UCB) algorithm for a contextual bandit problem. It defines a `ContextualBandit` class to represent the environment and a `UCB_Agent` class to represent the agent. The agent selects actions based on the UCB algorithm and updates its knowledge based on the rewards it receives. The notebook also includes code to train the agent and visualize the results.

## Usage

To use these notebooks, you will need a Python environment with the following packages installed:

- numpy
- matplotlib
- seaborn
- pandas

You can run each notebook in a Jupyter environment. The notebooks include code to train the agents and visualize the results. You can adjust the number of states, actions, and episodes to fit your specific problem.

## License

This project is licensed under the terms of the MIT license.
