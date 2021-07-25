### Implementation

The NN Architecture is:

- A first Linear layer mapping the state to 64 neurons, followed by ReLU activation
- A second Linear layer mapping the 64 to another 64 neurons, followed by ReLU activation
- A third Linear layer mapping 64 to 4 neurons, representing the actions

The learning algorithm is a Deep Q Network with experience replay and fixed q-targets.

The learning can be improved by making extensions towards a Rainbow DQN implementation, such as prioritized experience replay and dueling DQN.
