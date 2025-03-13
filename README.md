## Overview

This project implements and compares three fundamental reinforcement learning algorithms: Policy Iteration, Value Iteration, and Epsilon-Greedy Q-learning. These algorithms are applied to the Frozen Lake environment, where an agent navigates a grid to reach a goal while avoiding hazardous cells.

## Algorithms Implemented

1. **Policy Iteration**: This algorithm iteratively evaluates and improves a policy to find the optimal policy for the Frozen Lake environment.
2. **Value Iteration**: This algorithm iteratively updates the value function until convergence to determine the optimal policy.
3. **Epsilon-Greedy Q-learning**: This algorithm uses Q-learning with an epsilon-greedy exploration strategy to learn the optimal policy through interaction with the environment.

## Environment: Frozen Lake

The Frozen Lake environment is a grid-based world where:
- The agent starts in the bottom-right corner.
- The goal is in the top-left corner.
- Each cell can be safe (frozen), dangerous (hole), or the goal.
- The agent can move left, right, up, or down.
