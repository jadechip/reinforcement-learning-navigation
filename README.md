[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation

:banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana:
:banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana:
<br/>
:banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana:
:banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana:
<br/>
:banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana:
:banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana: :banana:

### Introduction

The goal of the project is to train an agent to navigate (and collect bananas!) in a large, square world.  

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  


## Environment details

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

```
    0 - move forward.
    1 - move backward.
    2 - turn left.
    3 - turn right.
```

The task is episodic, and in order to solve the environment, the agent must achieve an average score of +13 over 100 consecutive episodes.


## Setup

1. Optionally create a virtual environment

```
python -m venv drlnd
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Start the Jupyter server

```
jupyter notebook
```

## Links

1. [Report](https://skogman.github.io/drnd-project-01/)

2. [Weights](./checkpoint.pth) 
