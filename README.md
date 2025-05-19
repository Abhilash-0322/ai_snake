# AI Plays Snake

This project implements a Deep Q-Learning (DQN) agent that learns to play the classic Snake game.

## Project Structure

The project is organized into the following key Python files:

-   `game.py`: Implements the Snake game environment using Pygame. This is where the game logic, display, and user interaction (if any) would be handled.
-   `agent.py`: Implements the DQN agent. This includes the agent's learning algorithm (Q-learning), experience replay memory, and the main training loop that orchestrates the interaction between the agent and the game environment.
-   `model.py`: Defines the neural network architecture used by the DQN agent. This network takes the game state as input and outputs Q-values for each possible action, approximating the expected future rewards. It also includes the training mechanism for this network.
-   `helper.py`: Contains utility functions, such as a function to plot the agent's training progress (scores over time).
-   `requirements.txt`: Lists the necessary Python packages to run the project (e.g., Pygame for the game, PyTorch for the neural network, NumPy for numerical operations, Matplotlib for plotting).
-   `model/model.pth`: This file likely contains a pre-trained state of the neural network model, allowing one to load and use or continue training the agent.

## Technology Used

-   **Python:** The primary programming language.
-   **Pygame:** A library used for creating the Snake game environment and handling its graphics.
-   **PyTorch:** A deep learning framework used to build and train the neural network for the DQN agent.
-   **Deep Q-Network (DQN):** The reinforcement learning algorithm used to train the agent.
-   **NumPy:** Used for numerical computations, especially for handling game states and actions.
-   **Matplotlib:** Used for plotting the training progress.

## How to Run

(Instructions on how to run the training or play the game would typically go here, e.g., `python agent.py` to start training)
