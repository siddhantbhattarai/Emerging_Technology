### Task 6 (Cartpole Problem)
#### Question A: Define the Action Space for the Cartpole Problem
The action space in the Cartpole problem is discrete. Specifically, there are two possible actions:
1. Apply a force to push the cart to the left.
2. Apply a force to push the cart to the right.

This discrete nature means the agent selects from a finite set of actions at each time step, as opposed to a continuous action space where actions could have infinite possibilities between minimum and maximum values.

**Harvard Reference:**
Brockman, G., et al. (2016). OpenAI Gym. [online] Available at: <https://www.gymlibrary.dev/environments/classic_control/cart_pole/> [Accessed 12 Dec. 2024].

#### Question B: How Is the Reward Defined?
The reward in the Cartpole problem is structured to encourage the agent to keep the pole upright for as long as possible. A reward of +1 is given for each time step the pole remains balanced. The episode ends when:
- The pole falls beyond a certain angle threshold.
- The cart moves out of the defined track bounds.

This sparse reward structure allows the agent to learn the optimal policy through trial and error.

**Harvard Reference:**
Sutton, R. and Barto, A. (2018). Reinforcement Learning: An Introduction. 2nd ed. Cambridge, MA: The MIT Press.

---

### Task 6 (Deep Learning in rl_action.py)
#### Question A: Effect of Changing the Number of Epochs to 100
Increasing the number of epochs to 100 means the model will train over more iterations, potentially allowing it to better optimize its policy. This could lead to improved performance, as reflected in higher average rewards during testing. However, excessive epochs without proper regularization might also cause overfitting.

**Observation:**
When executed, the output will showcase higher cumulative rewards across episodes. Screenshots from the terminal and reward plot can visually confirm the improvement.

#### Question B: Changing the Learning Rate to 0.001
A lower learning rate (e.g., 0.001) slows down the rate at which the model updates its weights. This often leads to smoother but slower convergence. If the learning rate is too low, the model might take significantly longer to reach an optimal solution.

**Observation:**
Executing the program with the adjusted learning rate will show gradual reward improvements, indicating slower learning.

#### Question C: Discuss the Idea of Discounted Reward
![Screenshot from 2024-12-12 14-35-19](https://github.com/user-attachments/assets/74e06c07-b5a5-47d3-ab12-d291ee0fba76)

**Harvard Reference:**
Sutton, R. and Barto, A. (2018). Reinforcement Learning: An Introduction. 2nd ed. Cambridge, MA: The MIT Press.

---

### Task 7 (Snake Game)
#### Question A: Define the Action Space
In the Snake game, the action space is discrete, consisting of four possible moves:
1. Move up.
2. Move down.
3. Move left.
4. Move right.

#### Question B: Increasing the Maximum Number of Games
When the maximum number of games is increased to 100, the agent has more opportunities to learn and optimize its policy. This extended training can lead to higher scores and improved gameplay. The terminal and gameplay score outputs will illustrate the improvement.

**Harvard Reference:**
Mnih, V., et al. (2015). Human-level control through deep reinforcement learning. *Nature*, 518(7540), pp.529–533.

---

### Task 8: Additional Theoretical Questions
#### Question A: Brief Explanation of Markov Decision Process (MDP)
A Markov Decision Process (MDP) is a mathematical framework for modeling decision-making situations. It comprises:
- States (\(S\)): The possible configurations of the environment.
- Actions (\(A\)): The possible actions an agent can take.
- Transition probabilities (\(P\)): The probability of moving from one state to another.
- Rewards (\(R\)): The reward received for transitions between states.
- Discount factor (\(\gamma\)): The weight given to future rewards.

**Harvard Reference:**
Bellman, R. (1957). A Markovian Decision Process. *Journal of Mathematics and Mechanics*, 6(5), pp.679–684.

#### Question B: Q-learning vs. Deep Q-learning
Q-learning is a model-free reinforcement learning algorithm that uses a Q-table to estimate the value of state-action pairs. Deep Q-learning replaces the Q-table with a neural network, enabling the agent to handle high-dimensional state spaces.

**Harvard Reference:**
Mnih, V., et al. (2015). Human-level control through deep reinforcement learning. *Nature*, 518(7540), pp.529–533.

#### Question C: RL and Generative AI
Reinforcement learning can complement generative AI by optimizing generative models, particularly in tasks requiring sequential decision-making or fine-tuning (e.g., language generation with reinforcement learning via rewards for achieving conversational goals).

**Harvard Reference:**
Silver, D., et al. (2017). Mastering Chess and Shogi by Self-Play with a General Reinforcement Learning Algorithm. *arXiv preprint arXiv:1712.01815*.

---
