# GridWorld__RL1

Overview

This notebook implements a simple Reinforcement Learning (RL) experiment in a Grid World environment.
An agent learns to navigate a 10×10 grid, avoid obstacles, and collect randomly placed goals using Q-Learning.

Key Components

Custom Environment (GridWorldRL)
Defines grid size, obstacles, goals, and movement logic.

Agent Behavior
The agent explores using an ε-greedy strategy and updates Q-values based on rewards.

Rewards System

+10 for collecting a goal

+50 when all goals are collected

−0.1 per step, −1 for hitting walls or obstacles

Learning Parameters

Learning rate α = 0.1

Discount factor γ = 0.95

Epsilon decay from 1.0 → 0.01

Visualization

The notebook includes grid visualizations showing:

Obstacles and goals

Agent movement path

Learning progress over episodes (animation)
