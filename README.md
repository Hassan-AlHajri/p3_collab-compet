# p3_collab-compet Project
This repository contains the solution for the second project of the Udacity Deep Reinforcement Learning Nanodegree.

# Environment
In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, the agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

After each episode, the rewards that each agent received are added up(without discounting), to get a score for each agent. This yields 2 (potentially different) scores. Then, the maximum of these 2 scores is taken.
This yields a single score for each episode.
The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

# Requirements
pip install unityagents
pip install numpy
pip install matplotlib
install pytorch following the instructions on the pytorch website: https://pytorch.org/get-started/locally/

# Instruction

Run Tennis which is the notebook that contains the solution of the environment.

