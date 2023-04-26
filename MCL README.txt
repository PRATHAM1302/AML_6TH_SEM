MCModelv1 Function

This code defines a function called MCModelv1 which is used to implement a Monte Carlo model for a given dataset.


Required Packages

pandas
numpy
matplotlib


Function Parameters

data: pandas dataframe. This is the dataset that the model will use for training.

alpha: float. Learning rate of the algorithm.

e: int. Number of episodes to run the algorithm for.

epsilon: float. Epsilon value for epsilon-greedy selection.

budget: float. The total budget available for the decision-making process.

reward: float. The reward value for each action. Currently not in use.


Function Description

The function defines the states and initialises V_0 for each action. It then iterates over the number of episodes specified, and for each episode, it applies epsilon-greedy selection. The optimal action for each episode is output along with the sum of V(a) for all episodes. 

The function then returns SumofV, SumofVForCheapest, SumofVForExpensive, OptimalActions, data, ActionsSelectedinTime.