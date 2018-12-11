# OpenAIGym-Solutions
A collections of solutions for openai gym environments, using mainly reinforcement learning techniques.

## [MountainCar-v0](https://github.com/amohamed11/OpenAIGym-Solutions/tree/master/MountainCar)  

### Agent:
A Sarsa(λ) Agent with eligibility trace and linear function approximation was used for this solution.
Used to generate the feature vectors is the [tiles3](http://incompleteideas.net/tiles/tiles3.html) library

### Environment 
The bulk of the environment code is from the [RandomAgent](https://github.com/openai/gym/blob/master/examples/agents/random_agent.py) example on the OpenAI github.   
Modified to run the agent as necessary.  
Max Episode = 1000  
Initial reward = -1  

### Solution 
*Video to be posted*   
Required Avg score over 100 consecutive episodes = -110.00   
Achieved Avg score over 100 consecutive episodes = **-109.43**   
Number of Episodes for solution = **340**

![](https://github.com/amohamed11/OpenAIGym-Solutions/blob/master/MountainCar/rewardPerEpisode.png)
