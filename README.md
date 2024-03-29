# Project 1: Navigation - Udacity DRL Nanodegree
Implementation of a Deep Reinforcement Learning agent to solve the Unity Banana Collector environment. 

This repository contains all the material relative to the implementation of the Project 1 of the [Udacity Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) program. 


## The Environment
The environment consists of a large squared place where bananas should be collected. 

![banana](https://user-images.githubusercontent.com/36470989/60094173-99315800-974b-11e9-8e20-d422010be1e3.gif)


### State Space
- **Size:** 37

- **Content:** Agent Velocities + Ray based perception in the agent's forward direction

### Action Space
- **Size**: 4

- **Actions:** 0 = :arrow_up: ; 1 = :arrow_down: ; 2 = :arrow_left: ; 3 = :arrow_right:

### Reward

- **+1** : for collecting a yellow banana
- **-1** : for collecting a blue banana

### Goal

The environment is considered solved when the agent gets an average score of *+13* over 100 consecutive episodes

## Installation

Follow the instructions below to install the software necessary to run the agent in the environment. 

**1.** Set up the Python environment on your machine by following the [instructions in the DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies). 

**2.** Download the Unity environment:
- [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
- [Mac OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
- [Windows 32-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
- [Windows 64-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

**3.** Place the unzipped folder just downloaded in the `p1_navigation/` folder in the DRLND GitHub repository.

**4.** Clone [this repository](https://github.com/matteolucchi/udacity-drl-p1-navigation) in the `p1_navigation/` folder in the DRLND GitHub repository.

## How to run the code

The agent can be tested and trained in the [Navigation.ipynp](https://github.com/matteolucchi/udacity-drl-p1-navigation/blob/master/Navigation.ipynb) python notebook. Following the instructions in the notebook it is possible to see our trained agent in action or to train a new agent using the hyperparameters of your choice and to see your agent in action. 

