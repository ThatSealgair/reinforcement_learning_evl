# The Markov Decision Process (MDP)
## Elements Common to All Control Tasks
1. State (at the moment in time)
- State is always linked to a moment in time.
2. Actions (carried out during the control task)
- Chosen based on the state of the task and linked to a moment in time.
3. Reward (effectiveness of the decision)
- The greater the rewards we get, the better at achieving the goal
4. Agent (entity that will participate)
5. Enviroment (all aspects of the task that the agent does not control)

## Markov Decision Process (MDP)
- A Discrete-time stochastic control process
  - Time moves forward in finit intervals
  - Future states depend only partially on the actions taken
  - It is based on decision making to reach the target state

Let $S$ be the set of possible states of the task.
Let $A$ be the set of actions that can be taken in each of the states.
Let $R$ be the set of rewards for each $(s, a)$ pair.
Let $P$ be the probabilities of passing from one state to another when taking each possible action.

Then the Markov Decision Process is $M(S, A, R, P)$

### Property of MDP
- The next state depends only on the current state, not the previous one.
- i.e the process has no memory
$$P[S_{t+1}\vert S_{t}=s_{t}]= P[S_{t+1}\vert S_{t}=s_{t}, S_{t-1}=s_{t-1}, ..., S_{0}=s_{0}]$$



# Dynamic Programming

# Monte Carlo Methods

# Temporal Difference Methods

# N-Step Bootstrapping

# Continues State Spaces

# Brief Introduction to Neural Networks

# Deep SARSA

# Deep Q-Learning

# Reinforce

# Advantage Actor-Critic (A2C)

