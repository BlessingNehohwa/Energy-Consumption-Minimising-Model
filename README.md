# Energy-Consumption-Optimising-Model
Use Deep Q-Learning model to optimize energy consumption of a data center

This project leverages an AI deep learning model to optimize and reduce the energy consumption of a data center by up to 70%.


[Energy Consumption Optimisation Model Code](https://github.com/BlessingNehohwa/Energy-Consumption-Minimising-Model/blob/main/Energy%20Consumption%20Optimising%20%20Model-checkpoint.ipynb).
# Q-Learning
Q-Learning is a reinforcement learning algorithm to learn quality of actions telling an agent what action to take under what circumstances. It determines the value of all possible actions given a certain state (or circumstances). It does not require a model of the environment as it learns the environment while exploring it.   

Reminder (wikipedia): Reinforcement learning involves an agent, a set of states S, and a set A of actions per state. By performing an action a in A, the agent transitions from state to state. Executing an action in a specific state provides the agent with a reward (a numerical score). The goal of the agent is to maximize its total reward. It does this by adding the maximum reward attainable from future states to the reward for achieving its current state, effectively influencing the current action by the potential future reward. This potential reward is a weighted sum of the expected values of the rewards of all future steps starting from the current state.

The learning phase uses the "Experience Replay" technique to train.

![](https://github.com/BlessingNehohwa/Energy-Consumption-Minimising-Model/blob/main/Q_Learning_Neural%20_Network.png)


# Results

The percentage of energy saved varies depending on the experiments. The percentage is determined simulating one full year cycle.

![](https://github.com/BlessingNehohwa/Energy-Consumption-Minimising-Model/blob/main/Energy%20Saved.png)
