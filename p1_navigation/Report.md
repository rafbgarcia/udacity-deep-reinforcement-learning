[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

![Trained Agent][image1]

### Implementation

The NN Architecture is:

- A first Linear layer mapping the state to 64 neurons, followed by ReLU activation
- A second Linear layer mapping the 64 to another 64 neurons, followed by ReLU activation
- A third Linear layer mapping 64 to 4 neurons, representing the actions

The learning algorithm is a Deep Q Network with experience replay and fixed q-targets.

The learning can be improved by making extensions towards a Rainbow DQN implementation, such as prioritized experience replay and dueling DQN.
