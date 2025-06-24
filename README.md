# Reinforcements_Leaning
## Multi-Armed Bandit Exploration Strategies
Reinforcement Learning Project

This project implements and compares several action-selection strategies for solving the multi-armed bandit problem — a foundational problem in reinforcement learning. The goal is to identify strategies that balance exploration and exploitation to maximize long-term reward.

# Project Structure
RL10_arm_ali_hamad.ipynb     # Main Python notebook
/results/                    # Generated plots and performance comparisons (optional)

# Objectives
Simulate a 10-armed bandit environment.

Evaluate different action-selection algorithms:

Greedy

Epsilon-Greedy (ε = 0.1, 0.01)

Softmax

Upper Confidence Bound (UCB)

Measure performance using:

Average reward over time

Percentage of optimal actions selected
# Algorithms Implemented
| Algorithm          | Description                                                      |
| ------------------ | ---------------------------------------------------------------- |
| **Greedy**         | Always chooses the action with the highest estimated value       |
| **Epsilon-Greedy** | Chooses a random action with ε probability, greedy otherwise     |
| **Softmax**        | Selects actions probabilistically using a Boltzmann distribution |
| **UCB1**           | Balances exploration based on confidence bounds                  |

# Evaluation Metrics
Average Reward: Measures how effective each policy is over time.

% Optimal Action: Tracks how often the agent selects the true best arm.

Visual results are shown using two plots:

Reward vs. Steps

% Optimal Action vs. Steps
