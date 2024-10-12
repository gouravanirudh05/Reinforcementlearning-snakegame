# Reinforcementlearning-snakegame
This project applies Deep Q-learning to train an agent to play the classic Snake game. The goal is to enable the agent to improve over time and eventually perform as well as, or better than, a human player.
##  Track:
Machine Learning (ML)
## Problem Statement:
To train an agent that learns through reinforcement to excel at playing the Snake game after substantial training.
## Goal:
Leverage Deep Q-learning to train the system agent to play a custom Snake game implemented from scratch. 
## Tech Stack:
* Python
    * PyTorch (for building and training neural networks)
    * Pygame (for game development)
    * Matplotlib (for visualizing results)
    * Ipython (for interactive sessions)
    * Random (for random number generation)
    * Numpy (for array operations)
    * Collections (for data structures)
    * Enum (for enumerations)

## How to Run:

### Setup Environment
1. Clone the repository and navigate to the project directory:
   ```bash
   git clone https://github.com/gouravanirudh05/Reinforcementlearning-snakegame.git
   cd  Reinforcementlearning-snakegame
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the main file to start the game and training process:
   ```bash
   python agent.py
   ```
## Gameplay & Training
- Two windows will open:
  1.The game window, displaying the Snake game.
  2.A graph window, showing the current score and a rolling average of scores across games.
- The agent will learn over the course of many games (recommended: ~150 games). Watch the agent improve its performance over time.
## Applications:
 This approach can be generalized to other games by adjusting:
 - Game state parameters
 - Reward functions
 - Complexity of the neural network
We chose the Snake game to focus on learning and implementing everything from scratch in our first hackathon. However, the framework could be extended to more complex games.
## Further Improvements:
* UI Enhancement: The game's interface could be made more visually appealing.
* Game Elements: Adding features like bonus points, score multipliers, or additional obstacles for greater gameplay depth.
* Model Optimization:
  -  More layers could be added to the neural network for increased accuracy.
  - The reward function could be fine-tuned.
  - Better handling of the exploration-exploitation tradeoff, with more exploration at the beginning, could further improve learning.

## Conclusion
Despite its simplicity compared to other projects, we built everything from the ground up, including the game, and focused on the core concepts of reinforcement learning. This contrasts with others who may have used pre-trained models and simply combined them with a fancy UI. We believe our project is more aligned with the Machine Learning track as it applies core ML principles.

## Demo Video:
Check out a demo of the game [here](https://youtu.be/b_aoi2JPUTY).

