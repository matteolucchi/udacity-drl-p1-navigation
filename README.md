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
