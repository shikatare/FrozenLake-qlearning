# FrozenLake-qlearning
A reinforcement learning agent using Q-learning on the FrozenLake-v1 environment with training, evaluation, and agent path visualization.

## 🧠 What is FrozenLake?

FrozenLake is a grid world where the agent must reach the goal without falling into holes. The environment is stochastic, meaning actions may not always lead to the expected result.

- `S`: Start
- `F`: Frozen tile (safe)
- `H`: Hole (danger)
- `G`: Goal (destination)

---

## 🚀 Project Features

- ✅ Q-Learning implementation 
- 📊 Evaluation with average rewards
- 🎥 Visualization of the agent’s path using a generated GIF
- 📉 Exploration decay (epsilon-greedy strategy)

## 🧠 Q-Learning Overview

- **Episodes**: 20,000
- **Max Steps per Episode**: 100
- **Exploration Strategy**: ε-greedy
- **Learning Rate (α)**: 0.7  
- **Discount Rate (γ)**: 0.99  
- **Exploration Decay**: From 1.0 to 0.0001
The agent updates its Q-table as it learns the best actions for each state using the Bellman equation.

## Install Dependencies:
-pip install -r requirements.txt


  
  
