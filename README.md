# DQN-based Pommerman Agent

The goal of this project was to train an agent in Open AI's Pommerman environment, which participated in a multi-agent challenge setting. A Deep-Q-Network (DQN) approach is used for training the agent, with the agent starting in both positions randomly. The network used is a rather simple 3-layer CNN with adaptive average pooing and ReLU activation, followed by a 3-layer fully connected head - also with ReLU activation - on top, mapping to the agent's action space.

The final agent (saved in ONNX format, see above) won 83% of the games against Pommerman environment's SimpleAgent.
