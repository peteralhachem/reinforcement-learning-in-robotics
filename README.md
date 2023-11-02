
# Sim-to-Real transfer of Reinforcement Learning policies in robotics.

In robotics, performing experimentations on real-life objects may be exhaustively expensive with a need for significant resources. 

Frameworks, such as [`Gymnasium`](https://gymnasium.farama.org/) has given the opportunity to perform a simulation of diverse environments based on ***Reinforcement Learning*** algorithms.

[`Mujoco`](https://gymnasium.farama.org/environments/mujoco/)
is a physics engine for facilitating research and development in robotics, biomechanics, graphics and animation, and other areas where fast and accurate simulation is needed.

Instructions on installing the [`MuJoCo`](https://gymnasium.farama.org/environments/mujoco/) engine can be found on their [website](https://mujoco.org/) and [GitHub](https://github.com/google-deepmind/mujoco) repository.

The environment used in this experiment is the [`Hopper`](https://gymnasium.farama.org/environments/mujoco/hopper/): a two-dimensional one-legged figure that consist of four main body parts - the torso at the top, the thigh in the middle, the leg in the bottom, and a single foot on which the entire body rests. The goal is to make hops that move in the forward (right) direction by applying torques on the three hinges connecting the four body parts. 

Further information about the hopper *observation space*, *action space* and *reward function* can be found on their [link](https://gymnasium.farama.org/environments/mujoco/hopper/).
## Authors

- [@peteralhachem](https://github.com/peteralhachem)

- [@leonorgomes](https://github.com/leonormgomes)

- [@karlwennestrom](https://github.com/karlwen95)


## Badges


![Static Badge](https://img.shields.io/badge/university-poliTO-green)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%233F4F75.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)


## Repository structure

``data\`` - `.zip` file of the *hopper environment*. It contains the regular hopper environment and the hopper with domain randomization.

- You can find instructions on how to extract the hopper in the notebook files.

``img\`` - contains all the relevant plots performed within the experimentation phase.

``src\`` - contains the files that represent that tasks implemented.

- `reinforcement_learning_algorithm` - refers to the task of training policies.

- `domain_randomization` - refers to the task of training policies on an environment with domain randomization. 

- `vision_based_reiforcement_learning` - refers to the task of training policies on image-like data that represents states of the hopper. 

``task\`` - contains an explanation of the task which our experimentation were based on with all the associate documents needed. 

