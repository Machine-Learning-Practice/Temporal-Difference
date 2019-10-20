# Temporal-Difference

## Environment
- State Space = Box(2,) (Continuous Coordinates)
- Action Space = {0, 1, 2}

```
A car is on a one-dimensional track, positioned between two "mountains". The goal is to drive up the mountain on the right; however, the car's engine is not strong enough to scale the mountain in a single pass. Therefore, the only way to succeed is to drive back and forth to build up momentum.
```

![](./gifs/1_random_agent.gif)

## Discretizing the Continuous State Space to Discrete Space
As the RL methods like MC and TD works on discrete space, we have to convert the environment state spance into discrete space.
![](https://www.researchgate.net/profile/Hermann_Meer/publication/220053939/figure/fig1/AS:305815731884036@1449923560542/Discrete-vs-continuous-time-and-discrete-vs-continuous-state-space-models.png)


# Temporal-Difference methods
Agents were trained only for 30000 episodes.

- ## SARSA(0) or TD

### Sudo Code
![](https://miro.medium.com/max/1952/1*7WZZgbJQr5lh86LRB2pbVg.png)

### Scores
![](./images/sarsa_scores.png)

### Learned Agent
![](./gifs/1_sarsa_agent.gif)

- ## SARSAMax or Q-learning
### Sudo Code
![](https://leimao.github.io/images/blog/2019-03-14-RL-On-Policy-VS-Off-Policy/q-learning.png)

### Scores
![](./images/q_scores.png)

### Learned Agent
![](./gifs/2_qlearning_agent.gif)

- ## Expected SARSA
### Sudo Code
![](https://parksurk.github.io/assets/images/2018-12-12-drlnd_1-5_temporal_difference_methods-post/output_48_0.png)

### Scores
![](./images/e_sarsa_scores.png)

### Learned Agent
![](./gifs/3_expected_sarsa_agent.gif)
