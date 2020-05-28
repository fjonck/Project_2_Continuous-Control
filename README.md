# Project 2: Continuous Control

### The Unity environment
In this project we are solving the "Reacher" environment using the open-source Unity plugin **Unity Machine Learning Agents (ML-Agents)**. We are using the variant with only a single agent. The main use-case of those environments is to use trained agents for multiple purposes. But we are using it for designing, training and evaluating the performance of our own agent. 

### The game and the rewards
The goal in the environment "Reacher" is to keep a double-jointed arm at a moving target location which is a ball moving in a circle around the arm. This goal is definined by the reward rule +0.1 for each time step the hand of the arm in the goal location.

![Reacher example](https://video.udacity-data.com/topher/2018/June/5b1ea778_reacher/reacher.gif)

### The action and state space
The continuous action space is a 4-dimensional vector, each entry between -1 and 1 and corresponding to torque applicable to two joints. 
The state space consists of the position, rotation, velocity, and angular velocities of the arm. It has 33 dimensions.

### The instructions for solving the environment
The environment is considered to be solved after having achieved an average score of 30 in 100 consecutive episodes. 

### The instructions for installing the environment
1. Clone the repository https://github.com/fjonck/Project_2_Continuous-Control
2. Open the notebook Continuous_Control.ipynb with Jupyter Notebook
3. In the menu, click on Cell -> Run All
4. Enjoy watching the Reacher Agent learn :)
