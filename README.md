
1. Project Overview

This project is the first in Udacity's Deep Reinforcement Learning Nanodegree, where I trained an agent to navigate and collect bananas in a large square world. The goal is to collect as many yellow bananas as possible while avoiding blue bananas, with rewards of +1 and -1 respectively.

2. Environment Details

The state space has 37 dimensions, including the agent's velocity and ray-based perception of objects around its forward direction. The agent must learn to select from four discrete actions: moving forward, backward, turning left, or turning right. The task is episodic, and the agent must achieve an average score of +13 over 100 consecutive episodes to solve the environment.

3. Methodology

In the Navigation.ipynb notebook:

-Initialized the agent
-Evaluated the state and action space
-Trained the agent using a Deep Q-Network (DQN) with a simple 3-layered neural network
-Iterated until the agent reached a threshold score of 15.0


4.Getting Started

To start working on this project, follow these steps:

Download the environment from the provided links, selecting the version that matches your operating system.
Place the file in your working folder and unzip it.
Begin working with the Navigation.ipynb notebook.