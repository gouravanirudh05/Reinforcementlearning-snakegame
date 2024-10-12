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
   git clone <repository-url>
   cd <repository-directory>
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
- 
## Applications:
Our idea can further be extended to train the system agent to control other games by just changing the game state parameters, the reward function and the complexity of the neural network, we went with a simpler game as this was our first hackathon and we wanted to implement everything from scratch. 

## Further Improvements:
* We could have had a better UI for the game or even chosen a more complicated game.
* We could have added other elements like bonus points or score multipliers etc. to make the game more fun.
* We could have implemented the model such that it was more accurate by either adding more layers to the neural network or even optimising the reward function, we could have also exploited the tradeoff between exploration and exploitation to try more random things at the start. 

## Conclusion
* We would like to end by saying that even though our idea does not seem as complicated as some others, we built everything including the game from the ground up as compared to others who have just used a bunch of pre-trianed models and combined them, also we feel that our project is more aligned with the track 'ML' than some others who have just built a great UI for their models.

## Demo Video:
* https://youtu.be/b_aoi2JPUTY
