```
 #############################################    
 # . WARSAW DEEP LEARNING LABS
 # . | | /| / / _ \/ /  / /     
 # . | |/ |/ / // / /__/ /__    
 # . |__/|__/____/____/____/    
 # .  S01E08 by Nextgrid.ai 👾
 #############################################    
 # Reinforcement learning 
 #############################################
```
# SUBMIT RESULT ON THIS LINK 
Soon.

# Warsaw Deep Learning Labs Episode #8

Here you will find instructions and relevant information for the event. Don't hesitate to reach out organizers with any kind of questions.

Feel free to jump in on our event [Slack channel](https://join.slack.com/t/warsawdeeplea-lin3168/shared_invite/enQtODEyMjA1NTE1NjA3LWQ0Y2Q2OGUwNzBmMjljMDA1NGZmMWFmZTEzZWRkZjlkOTQ1YTQ4OTI4MzdhMDBmNjhmOWEyZDkzNDQ4MTQ5Njg) where @Misha & @M are avalible to answer questions and help out with issues.

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











