# PPO Bipedal Walker - Reinforcement Learning Project

This repository contains the implementation of a Proximal Policy Optimization (PPO) algorithm applied to the Bipedal Walker environment from OpenAI Gym. This project demonstrates advanced reinforcement learning techniques and serves as a practical example for aspiring Machine Learning Engineers.

## Repository Contents

- **`PPO_Bipedal_Walker_Manuela_Larrea.ipynb`**: Jupyter Notebook with the complete implementation, training process, and evaluation of the PPO algorithm on the Bipedal Walker environment.
- **`requirements.txt`**: List of dependencies required to run the notebook.
- **`README.md`**: This file, providing an overview and technical details of the project.

## Project Overview

### Objective

The goal of this project is to train an agent to successfully navigate and control a bipedal walker using reinforcement learning. The PPO algorithm is chosen for its stability and efficiency in handling continuous action spaces.

### Environment

- **Environment**: Bipedal Walker v2
- **Library**: OpenAI Gym

### Algorithm

- **Proximal Policy Optimization (PPO)**: An advanced reinforcement learning algorithm that balances exploration and exploitation by iteratively updating policies based on the advantage function.

## Technical Details

### Data Preprocessing

- **State Normalization**: Standardize the states to ensure faster convergence.
- **Reward Shaping**: Modify rewards to provide better feedback signals to the agent.

### Model Architecture

- **Policy Network**: A neural network with fully connected layers to approximate the policy function.
- **Value Network**: A separate neural network to estimate the value function.

### Training Process

- **Episodes and Timesteps**: Define the number of episodes and timesteps per episode.
- **Learning Rate and Optimizer**: Utilize Adam optimizer with a carefully chosen learning rate for stable training.
- **Discount Factor (Gamma)**: Set to balance immediate and future rewards.

### Evaluation Metrics

- **Total Reward**: Sum of rewards received by the agent over an episode.
- **Average Reward**: Average of total rewards over multiple episodes to assess performance stability.

## Results

- **Training Curves**: Visualize the total and average rewards over training episodes.
- **Policy Visualization**: Demonstrate the learned policy by rendering the agent's performance in the environment.

## Requirements

- Python 3.7+
- Libraries: numpy, pandas, matplotlib, gym, stable-baselines3

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/PPO-Bipedal-Walker-ML-Engineer.git
