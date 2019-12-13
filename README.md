<h1>About</h1>

<h2>What Is Deep Reinforcement Learning</h2>

According to Wikipedia, Reinforcement Learning (RL) 'is an area of machine learning concerned with software taking actions so as to maximize a cumulative reward.'  Ultimately, RL is about 'building code that can perform complex tasks by itself.'  Deep Reinforcement Learning extends on the aforementioned 'by using a deep neural network and without explicitly designing the state space.'

<h2>Udacity's Deep Reinforcement Learning Nanodegree</h2>

This nanodegree teaches cutting-edge Deep Reinforcement Learning algorithms — from Deep Q-Networks (DQN) to Deep Deterministic Policy Gradients (DDPG) to train agents to walk, drive, or perform other complex tasks, and to build a robust portfolio of Deep Reinforcement Learning projects.  Nanodegree milestones include three projects, all of which have detailed requirements and instructions and all of which use the Unity Machine Learning Agents (ML-Agents) toolkit

<h1>Navigation (1st Project)</h1>

The first project requires training an agent to collect yellow bananas while avoiding blue bananas.  To be considered successful, the agent must be able to receive an average reward (over 100 episodes) of at least +13.

![alt text](https://video.udacity-data.com/topher/2018/June/5b1ab4b0_banana/banana.gif "")

When the agent collects a yellow banana, a reward of +1 will be awarded and a reward of -1 when a blue banana is collected. Hence, it stands to reason that the agent should learn to collect as many yellow bananas as possible while avoiding blue bananas.

At each time step, the agent may take one of four actions:

<li>0: Walk Forward
<li>1: Walk Bakcward
<li>2: Turn Left
<li>3: Turn Right

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

<h2>Prerequisites</h2>

The code must be written in PyTorch and Python 3.

<h1>Getting Started</h1>

<h2>Python</h2>

Set up the Python environment following the instructions in the link below:

https://github.com/udacity/deep-reinforcement-learning/#dependencies

<h2>Environment</h2>
  
Download the Unity environment (the following operating systems are supported):

[Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)<br>
[Mac OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)<br>
[Windows (32-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)<br>
[Windows (64-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)<br>

<h2>Project Files</h2>

Download the following project files:

<li>Navigation.ipynb
<li>model.py
<li>agent.py

<h2>Running Instructions</h2>

Open Navigation.ipynb and execute





