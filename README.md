# IBM Think Digital Summit 2020 Code Cafe RL experince

version 0.01, 2020.09.15

This is an introductory reinforcment learning workshop created by [Mathias Åsberg](https://www.linkedin.com/in/imathias/) and [Tomasz Brzozowski](https://www.linkedin.com/in/tomasz-brzozowski/) from [Nextgrid](https://nextgrid.ai).

![image of IBM Think Summit](https://nextgrid.ai/wp-content/uploads/2020/06/16_Think_Blue_1400x1400.jpg "Think")

## Agenda

**(1 hours 15 min in total)**

- Introduction with Mathias - 15 min
- Reinforcment learning on Watson Studio with Tomasz - 30 min

## Reinforcment Learning Hands-on

Reinforcement learning is a machine learning technique that learns how to maximize a reward by taking actions. A dog might try to learn how to maximize belly rubs through its barking, or a cat might try to learn how to maximize being annoying through its jumping. Both these animals are **AGENTS** taking **ACTIONS** based on their current **STATE**, trying to maximize the **REWARD**.

## Goal = maximize reward

The goal of the **AGENT** is to **maximize its total reward**. It does this by adding the maximum reward attainable from future states to the reward for achieving its current state, effectively influencing the current action by the potential future reward. This potential reward is a weighted sum of the expected values of the rewards of all future steps starting from the current state.

### Approach

We believe that people learn best by actuall getting hands on. Today is the 8-th mini hackaton event and the mission is to solve Hopper gym environment.

### Grading

Several tasks will be graded and starting from this event we will maintain leaderboard on our page with the best teams.
Today the ranking includes the following tasks (List will be expanded in next events):

- CartPole - 1 pt.
- HalfCheetah - 1 pt.
- LunarLander - 3 pt.
- BipedalWalker - 6 pt.
- Hopper - 12 pt.

Extra 20% points to each task in case when team will make something special, like good presentation with insights or non-standard solution of the problem.
In case of unsucessfull trial, team still can get points proportional to their result.
For example, cartpole is solved when score is above 190, so if team has score 95 (half of solved) it will get half of the points for this task - 0.5 pt.

### Instructions

1. Pick a enviorment from the list above.
2. Work as a team, pause for 5 min every 30 min to discuss current status, what is being done and why it matters.
3. If you get stuck we are here to help.
4. Instructions & template for submitting will be avalible during day.

### Notebooks

Here is notebooks covering a couple of enviorments & algoritms and can be used as fundation.  
 [Github with notebooks](https://github.com/nextgrid/notebooks)  
 [Stable-baselines walk-through](https://colab.research.google.com/drive/1vuBn_JJV9Xyd4O_RpCMqk8Iv_ua9Zq_N)  
 [Video-recording_cheatsheet](https://colab.research.google.com/drive/1i48t8xkoTKYO4gcR4Sn8T7bGxBy0T4OH)  
 [Bipedalwalker-V2_TD3_Tensorboard](https://colab.research.google.com/drive/1Zyn9Q_Gf3KnVIhdl9t2ond5IjJNaTriL)  
 [Lunar-Lander_TD3_Tensorboard](https://colab.research.google.com/drive/1_ZndTOt88TuXG2imZLb3ylU2C3nH9T-i)  
 [Pendulum_TD3](https://colab.research.google.com/drive/1_UhnDQE8NgSYGpUEAj0xgYI8Qvh7a6HK)

### Links

1. [https://stable-baselines3.readthedocs.io/en/master/](https://stable-baselines3.readthedocs.io/en/master/)
2. [https://cloud.ibm.com/](https://cloud.ibm.com/)
