# Useful notes about reinforcement learning

## 1. What is the difference between off-policy and on-policy learning?
- In **on-policy** learning the 𝑄(𝑠,𝑎) function is learned from actions, we took using our current policy 𝜋.
- In **off-policy** learning the 𝑄(𝑠,𝑎) function is learned from different actions (for example, random actions). We even don't need a policy at all!
[Here](https://stats.stackexchange.com/questions/184657/what-is-the-difference-between-off-policy-and-on-policy-learning) is a good reference.

## 2. What is bootstrapping in reinforcement learning?
Bootstrapping in RL can be read as "using one or more estimated values in the update step for the same kind of estimated value". See [here](https://datascience.stackexchange.com/questions/26938/what-exactly-is-bootstrapping-in-reinforcement-learning) for more details.

## 3. Exploration vs exploitation trade-off
[Here](https://towardsdatascience.com/exploration-in-reinforcement-learning-e59ec7eeaa75) is a good reference.

## 4. What is the main difference between reinforcement learning and other machine learning paradigms? (Answer taken from David Silver's [lecture](https://www.davidsilver.uk/teaching/))
- There is no supervisor, only a reward signal
- Feedback is delayed, not instantaneous
- Time really matters (sequential, non i.i.d data)
- Agent’s actions affect the subsequent data it receives
