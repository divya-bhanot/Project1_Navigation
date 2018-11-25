# Project1_Navigation
Deep reinforcement learning Navigation project

[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"


### Introduction

For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.  

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Getting Started

1. Using the workspace provided by udacity . Implementation is done using single python notebook by defining all
the required code componenets like replay memory, agent advances like how to select next action, which is next state
and doing a learning update at desired frequency.

Description for code files in git https://github.com/divya-bhanot/Project1_Navigation/:
Navigation.ipynb : It includes all the code base along with comments which defines model , agent and training the agent
Navigation.html: Html version of above jupyter notebook
savepoint.pth: Saved model weights of the successful agent.
unit-environment.log : log file from unity environment 
README.md: Environment set up instructions as well as code base description
Report.pdf: Final report for project

2. After successfully running the code, create a new git repo, clone the repositery to local and add all the code and required documentation
files. Commit the code and push the branch to remote repo. 

### Instructions

Follow the instructions in the code file  `Navigation.ipynb` to get started with training your own agent!  



