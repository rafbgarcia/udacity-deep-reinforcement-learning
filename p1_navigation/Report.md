### Implementation

The NN Architecture is:

- A first Linear layer mapping the state to 64 neurons, followed by ReLU activation
- A second Linear layer mapping the 64 to another 64 neurons, followed by ReLU activation
- A third Linear layer mapping 64 to 4 neurons, representing the actions' rewards.

The learning algorithm is a Deep Q Network with experience replay and fixed q-targets.

The learning can be improved by making extensions towards a Rainbow DQN implementation, such as prioritized experience replay and dueling DQN.

I played with different hyperparameters and found out that updating the target DQN every 2 episodes instead of 4, and setting the epsilon decay to 0.98 instead of 0.995, trains it quicker.
