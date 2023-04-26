[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135612-cbff24aa-7d12-11e8-9b6c-2b41e64b3bb0.gif "Trained Agent"

# Deep Q-Network (DQN)

## Installation

### Prerequisites

To run this project, you will need to have anaconda or mini conda already installed:
create a virtual environment with the following.
To begin open your anaconda terminal and clone this repository 
```bash
git clone https://github.com/sokistar24/Deep_Reinforcement_learning
```
```bash
conda create --name intro_to_rl python=3.9 jupyterlab numpy matplotlib
```
Activate the environment uisng 
```bash
conda activate intro_to_rl

```
```bash
pip install gymnasium[box2d]
```
To start the JupyterLab server, run the following command 
in the terminal or command prompt:
```bash
jupyter-lab
```
### Instructions

In this exercise, you will implement Deep Q-Learning to solve OpenAI Gym's LunarLander
environment.  


navigate to the `Deep_Q_lunar_landar.ipynb/` and run the notebook

try to change the parameters in the notebook, to see if you can get the agent to train faster!
You may also like to implement prioritized experience replay, or use it as a starting point to implement a Double DQN or Dueling DQN!

### Results

![Trained Agent][image1]

### Resources

- [Human-Level Control through Deep Reinforcement Learning](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf)
- [Deep Reinforcement Learning with Double Q-Learning](https://arxiv.org/abs/1509.06461)
- [Dueling Network Architectures for Deep Reinforcement Learning](https://arxiv.org/abs/1511.06581)
- [Prioritized Experience Replay](https://arxiv.org/abs/1511.05952)
