# Reinforcement Learning Agents with Q-Learning

This project demonstrates the implementation of tabular Q-Learning agents in OpenAI Gym environments. The main objective is to train agents that can learn optimal decision-making policies through exploration, exploitation, and reward-based learning.

## Project Overview

Reinforcement Learning is a machine learning approach where an agent learns by interacting with an environment and improving its actions based on rewards.

This project focuses on two classic OpenAI Gym environments:

- Taxi-v3
- CartPole

The project applies Q-Learning to train agents, evaluate learning performance, and analyze how exploration strategy affects agent behavior over time.

## Objectives

- Implement tabular Q-Learning from scratch
- Train an agent in the Taxi-v3 environment
- Apply state discretization for the CartPole environment
- Use epsilon-greedy exploration
- Track cumulative rewards during training
- Analyze the effect of epsilon decay
- Evaluate learned policies after training

## Key Concepts

- Reinforcement Learning
- Q-Learning
- Epsilon-greedy exploration
- Exploration vs exploitation
- Reward optimization
- State-action value learning
- Discretization of continuous state space
- OpenAI Gym environments

## Environments

### Taxi-v3

Taxi-v3 is a discrete environment where the agent learns to pick up and drop off passengers at correct locations while minimizing penalties and unnecessary actions.

### CartPole

CartPole is a continuous-control environment where the agent learns to balance a pole by moving a cart left or right. Since tabular Q-Learning requires discrete states, the continuous state variables are converted into bins.

## Repository Structure

```text
reinforcement-learning-qlearning-agents/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   └── q_learning_openai_gym.ipynb
│
├── src/
│   └── q_learning_agents.py
│
├── reports/
│   └── reinforcement_learning_report.pdf
│
└── results/
    └── README.md
