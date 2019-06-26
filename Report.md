# Report

## Descritpion of the learning algorithm

#### Hyperparameters chosen

- minibatch size: 64
- replay memory size: 10000
- discount factor gamma: 0.99
- min squared gradient tau: 0.01
- learning rate: 0.001
- agent history length: 4
- initial exploaration: 1.0
- final exploration: 0.01
- exploration decay factor: 0.995

#### Model Architecture

## Performance of the trained agent
The agent solved the environment, by obtaining an average score over 100 episodes higher than 13.0 , in a total of **433** episodes.

**Trained agent**

![trained_agent](https://user-images.githubusercontent.com/36470989/60196570-bb0b0780-983d-11e9-8e28-4e83a5a464af.gif)



**Plot of the rewards obtained by the agent during the training**

![reward_plot](https://user-images.githubusercontent.com/36470989/60191450-9f4f3380-9834-11e9-8f5e-8061601466d0.png)

## Future improvements

To improve the performance of the algorithm some of the suggestions for future work are:
- implementation of [Double DQN](https://arxiv.org/abs/1509.06461)
- using a [Prioritized experience replay](https://arxiv.org/abs/1511.05952)
- trying to use a deeper neural network 
