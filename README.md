```
 #############################################    
 # . WARSAW DEEP LEARNING LABS
 # . | | /| / / _ \/ /  / /     
 # . | |/ |/ / // / /__/ /__    
 # . |__/|__/____/____/____/    
 # .  S01E03 by Nextgrid.ai 👾
 #############################################    
 # Reinforcement learning 
 # OpenAI gym, Stable-baselines Tensorflow and Keras
 #############################################
```

# Warsaw Deep Learning Labs Episode #3

Here you will find instructions and relevant information for the event. Don't hesitate to reach out organizers with any kind of questions.

Feel free to jump in on our event [Slack channel](https://join.slack.com/t/warsawdeeplea-lin3168/shared_invite/enQtNzY3NTE5MTU0NjI5LTljMGY4MmIwODNiNDYwZGIzMzAxNDE3YTVjODdmN2U3NTdkMzQwMjYyOWFjODUzMjIyMWNhOGExZDc2ZDc0NzQ) where @Marek & @M are avalible to answer questions and help out with issues.

### Approach
We believe that people learn best by actually getting down and dirty. Today is the third mini hackaton event and the mission is to build a BipedalWalker-v2. We recommend looking at 

### Technologies 

1. Use technology of your coice 
2. We recommend checking out [https://github.com/hill-a/stable-baselines](https://github.com/hill-a/stable-baselines)


### Instructions

1. Work as a team, pause for 5 min every 30 min to discuss current status, what is being done and why it matters. 
2. Read [http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching_files/intro_RL.pdf](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching_files/intro_RL.pdf)

### Rules

1. BipedalWalker-v2 average reward over 100 consecutive episodes.  If avarage of 300 is reached go to #2
2. BipedalWalker-v2 Hardcore average reward over 100 consecutive episodes


```
import gym

from stable_baselines.common.policies import MlpPolicy
from stable_baselines.common.vec_env import DummyVecEnv
from stable_baselines import PPO2

# Create the environment
env = gym.make('BipedalWalker-v2')
env = DummyVecEnv([lambda: env])  # The algorithms require a vectorized environment to run

# Define the model
model = PPO2(MlpPolicy, env, verbose=1, tensorboard_log="./ppo_bipedal_tensorboard/")

# Train the agent
model.learn(total_timesteps=25000)

# After training, watch our agent walk
obs = env.reset()
for i in range(1000):
    action, _states = model.predict(obs)
    obs, rewards, dones, info = env.step(action)
    env.render()
```



