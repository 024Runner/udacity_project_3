<h1>About</h1>

<h2>What Is Deep Reinforcement Learning</h2>

According to Wikipedia, Reinforcement Learning (RL) 'is an area of machine learning concerned with software taking actions so as to maximize a cumulative reward.'  Ultimately, RL is about 'building code that can perform complex tasks by itself.'  Deep Reinforcement Learning extends on the aforementioned 'by using a deep neural network and without explicitly designing the state space.'

<h2>Udacity's Deep Reinforcement Learning Nanodegree</h2>

This nanodegree teaches cutting-edge Deep Reinforcement Learning algorithms — from Deep Q-Networks (DQN) to Deep Deterministic Policy Gradients (DDPG) to train agents to walk, drive, or perform other complex tasks, and to build a robust portfolio of Deep Reinforcement Learning projects.  Nanodegree milestones include three projects, all of which have detailed requirements and instructions and all of which use the Unity Machine Learning Agents (ML-Agents) toolkit

<h1>Collaboration and Competition (3rd Project)</h1>

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

<li>After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.

<li>This yields a single score for each episode.

The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

![alt text](https://raw.githubusercontent.com/saabrider/udacity_project_3/master/tennis.gif "")

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





