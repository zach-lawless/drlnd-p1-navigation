# drlnd-p1-navigation
Udacity Deep Reinforcement Learning Nanodegree Project 1 repository

---

## Project Details
The goal of this project is to train an agent that navigates in Unity's Banana Collector environment. The agent's goal specifically is to navigate the square environment and collect yellow bananas while avoiding blue bananas. The agent receives a reward of +1 for every yellow banana collected and a reward of -1 for every blue banana collected.

The state space for this environment is a vector of length 37, consisting of positional information about the agent as well as ray-based information about the surrounding area. There is an alternative state space representation of the environment that is solely pixel-based, but that representation was not used for this implementation.

The action space for the agent is a vector of length 4. The available actions that the agent can take are `{forward, backward, turn left, turn right}`. 

The environment is considered solved when the agent receives an average reward of 13 for the last 100 episodes.


## Getting Started
The easiest way to run this repository would be to clone it into an existing Udacity virtual workspace. This is because the Python requirements and install instructions in the Udacity DRLND Github repository is rather outdated, and the virtual workspaces provided already contain everything needed for execution. All development for this project was completed on the Udacity virtual workspace.

If it's desired to run this agent locally, clone the [DRLND Github repo](https://github.com/udacity/deep-reinforcement-learning/) and follow the setup instructions for the whole repository. From there, follow the project-specific instructions located under `p1_naviation`.

## Instructions
In order to train the agent, run `Navigation.ipynb` end-to-end. More details on each individual cell and the purpose are provided inside the notebook.