# Deep Q-Network (DQN) - Reinforcement Learning

This repository contains an implementation of **Deep Q-Network (DQN)**, a deep reinforcement learning algorithm that enables agents to learn optimal decision-making in environments modeled as Markov Decision Processes (MDPs). The implementation includes key enhancements such as **experience replay** and **target networks**, which improve stability and convergence.

## Features
- **Deep Q-Network (DQN) Implementation**: Uses a neural network to approximate Q-values and optimize decision-making.
- **Experience Replay**: Stores past experiences to break correlation and improve sample efficiency.
- **Target Network Stabilization**: Updates target Q-network periodically to reduce oscillations in training.
- **Customizable Hyperparameters**: Tune learning rate, epsilon decay, batch size, and more.
- **Performance Evaluation**: Tracks cumulative rewards, loss, and Q-values over training episodes.
- **Visualization Tools**: Graphs for loss, reward progression, and action distributions.
