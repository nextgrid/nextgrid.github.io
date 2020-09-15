# IBM Think Digital Summit 2020 Code Cafe RL experince

version 0.01, 2020.09.15

This is an introductory reinforcment learning workshop created by Mathias Åsberg and Brzozowski from [Nextgrid](https://nextgrid.ai).

![image of cat](https://nextgrid.ai/wp-content/uploads/2020/06/01_Think_Gray_1400x1400.jpg "Think")
Presented by [Nextgrid](https://nextgrid.ai

## Agenda

**(1 hours in total)**

- Introduction with Mathias - 15 min
- Reinforcment learning on Watson Studio with Tomasz - 45 min
- Preparation Lab - 15 min (**lab**)
  - [1-PrepareLab/README.md](1-PrepareLab/README.md)
- Watson Studio on IBM Cloud - running AutoAI experiment - 30 min (**lab**):
  - [2-WatsonStudioLab/README.md](2-WatsonStudioLab/README.md)
- Starting Visual Recognition Application on IBM Cloud - 30 min (**lab**)
  - [3-VisualRecognitionLab/README.md](3-VisualRecognitionLab/README.md)
- Watson OpenScale - 15 min (**demo**)
- Q&A
  - [4-ExtraStuffOpenAI/README.md](4-ExtraStuffOpenAI/README.md) ibm

)

## Reinforcment Learning Hands-on

Reinforcement learning is a machine learning technique that learns how to maximize a reward by taking actions. A dog might try to learn how to maximize belly rubs through its barking, or a cat might try to learn how to maximize being annoying through its jumping. Both these animals are **AGENTS** taking **ACTIONS** based on their current **STATE**, trying to maximize the **REWARD**.

## Goal = maximize reward

The goal of the **AGENT** is to **maximize its total reward**. It does this by adding the maximum reward attainable from future states to the reward for achieving its current state, effectively influencing the current action by the potential future reward. This potential reward is a weighted sum of the expected values of the rewards of all future steps starting from the current state.

## SUBMIT RESULT ON THIS LINK

[Google form](https://docs.google.com/forms/d/1ugf0AQbjQHyv_t04F5NynRFKKVdbic__GGveinDgTMg/edit)

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

### Environments

1. `CartPole-v0`, required reward: 190.
2. `HalfCheetah-v2`, required reward: 4800.  
   Requires MuJoCo (use remote server or reach organizers if you want to set it up locally)
3. `LunarLander-v2`, required reward: 200.
4. `BipedalWalker-v3`, required reward: 300.
5. **Main challenge:** `Hopper-v2`, required reward: best result.  
   Requires MuJoCo (use remote server or reach organizers if you want to set it up locally)

### Technologies

1. Use technology of your coice
2. We recommend checking out [https://stable-baselines.readthedocs.io/](https://stable-baselines.readthedocs.io/) and our [repo](https://github.com/nextgrid/notebooks) where we will maintain notebooks with useful info.
3. We recommend to use machine that we will provide to you. It is a google cloud VM with 16 CPU's and 60 GB of RAM.  
   1 machine per team, leaders will get credentials to it.  
   You will get IP and if you use `{IP}:8888` you will get to the visualization tools called Tensorboard and if you use `{IP}:6006` you will get Jupyter-Lab environment.
4. Another hardware option is to use [google colab](https://colab.research.google.com/)

**P. S.** If you have some special needs just ask us and he will make whatever machine you want :)

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

### Remote development over SSH

Each team has dedicated Virtual Machine hosted on Google Cloud Platform. You can work directly using SSH using VSCode or other IDE.
Ask organizers for the credentials!

### Materials

1. [https://towardsdatascience.com/teach-your-ai-how-to-walk-5ad55fce8bca](https://towardsdatascience.com/teach-your-ai-how-to-walk-5ad55fce8bca)
2. [https://github.com/araffin/rl-baselines-zoo/tree/master/hyperparams](https://github.com/araffin/rl-baselines-zoo/tree/master/hyperparams)
3. [https://github.com/openai/gym/wiki/Leaderboard](https://github.com/openai/gym/wiki/Leaderboard)
