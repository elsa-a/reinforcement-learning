# Deep Reinforcement Learning

Below, selected projects carried out for CS6482 on the topic of Deep Reinforcement Learning.

## Deep Q Networks and Dueling DQN implementation for Atari Pong: 

This project implements an agent that is capable of learning how to play Atari’s arcade game Pong through Deep Q Networks. This project uses OpenAI0's Gym framework for the ATARI Arcade Learning Environment, a joint platform that gathers a collection of hundreds of games that emulate 1980's Atari 2600 games.

In the early 2010’s Reinforcement Learning yielded numerous successful approaches in the optimisation of decision-making tasks as the one in question in this project. They mainly centred around Convolutional Neural Networks, LSTM and Autoencoders, as well as combinations of these and other neural architectures adapted into Reinforcement Learning ideas. One of the most relevant ones were the Deep Q Networks, which are a neural approach to control tasks based on the off-policy Q-Learning control paradigm. The DQN architecture achieved significant performance in the Atari Learning Environment, which is explored in this project, and became state-of-art in the field of Reinforcement Learning.

[Project report here](https://github.com/elsa-a/reinforcement-learning/blob/main/CS6482-Prj2-21272808-21077363-21251266-Report.pdf/).

[DQN implementation here](https://github.com/elsa-a/reinforcement-learning/blob/main/CS6482-Prj2-21272808-21077363-21251266-Regular-DQN-Pong.ipynb).

[Dueling DQN implementation (too big to visualise in github) here](https://github.com/elsa-a/reinforcement-learning/blob/main/CS6482-Prj2-21272808-21077363-21251266Dueling_DQN_with_Pong.ipynb).


##  DQN implementation for Breakout

Additional implementation of Deep Q Networks for the game Breakout:
[DQN Breakout implementation](https://github.com/elsa-a/reinforcement-learning/blob/main/CS6482-Prj2-21272808-21077363-21251266-Additional-Notebook-Breakout.ipynb)

## Policy Gradient implementation for the Cartpole problem

This project implements a policy gradient method in PyTorch.
Polivy gradients are a reinforcement learning technique that rely on optimising a parameterized policy for an expected reward (long-term cumulative reward) via gradient descent. They do not suffer from many of the problems of traditional reinforcement learning methods, such as the lack of guarantees on the value function, intractability due to indefinite state information, and complexity due to continuous states and functions.

[Policy Gradient report here](https://github.com/elsa-a/reinforcement-learning/blob/main/CS6482-Assign3-21272808-21251266%20.pdf).

[Notebook here](https://github.com/elsa-a/reinforcement-learning/blob/main/CS6482-Assign3-21272808-21251266%20.ipynb).

