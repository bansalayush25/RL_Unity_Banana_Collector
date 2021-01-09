# Banana Collector
This repository contains implementation of Reinforcement learning based on Deeq Q-Learning (DQN), Double DQN.
The target of the agent is to collect Yellow bananas in a square world as mentioned in [Unity Banana Collector](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#banana-collector).

For each yellow banana that is collected, the agent is given a reward of +1. The blue ones give -1 reward.

The agent has 4 actions:
1. move forward
2. move backward
3. turn left
4. and turn right

The environment is considered as solved if the agent is winning an average of +13 points for 100 consecutive episodes.
