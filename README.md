# 1. Introduction

Deep Q-Networks (DQN) have become a fundamental approach to reinforcement learning
by integrating deep neural networks with Q-learning. This report explores how different
**batch sizes** and target update rates impact the training performance of a DQN agent.
We experiment with four different hyperparameter settings:

1. Batch = 8, Target Update = 10
2. Batch = 16, Target Update = 10
3. Batch = 8, Target Update = 3

The goal is to determine which setting provides the best balance between learning
stability and performance.

2. Network Architecture
The Deep Q-Network (DQN) used in this experiment follows a convolutional neural
network (CNN) architecture to process visual input from the environment.

![- visual selection(1)](https://github.com/user-attachments/assets/cb486eb0-9819-4820-a931-4dd15766fdce)
