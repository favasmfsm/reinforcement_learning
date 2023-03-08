# Reinforcement learning projects

Reinforcement learning can be applied to numerous problems. Here we will be discussing about the various reinforcement learning projects for a beginner.

## Frozen Lake game

**Problem statement**: The Frozen Lake environment is a 4×4 grid which contain four possible areas  — Safe (S), Frozen (F), Hole (H) and Goal (G). The agent moves around the grid until it reaches the goal or the hole. If it falls into the hole, it has to start from the beginning and is rewarded the value 0. The process continues until it learns from every mistake and reaches the goal eventually.

**Installation**:

    pip install gym

## CartPole game

CartPole is a reinforcement game provided by OpenAI Gym. 
**Problem statement**: There is a cart to which a pole is attached which is unstable as the centre of mass of the pole is above the pivot point. 
The player is supposed to move the cart left or right to balance it. If the pole deviates more than 15 degrees, the game ends. 
Otherwise, for every timestamp that the pole deviates no more than 15 degrees, 1 point is rewarded to the agent.
