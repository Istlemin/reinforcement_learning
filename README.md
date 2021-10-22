# Reinforcement Learning

This repository contains my implementations of RL algorithms applied to the dm_control suite.

## DDPG

The file ddpg.ipynb implements the Deep Deterministic Policy Gradient algorithm, presented in [2]. After ~300000 iterations it gets the following result on the cartpole swingup task:

![ddpg_swingup](images/ddpg_swingup.png)


## Citations
[1] Tassa, Yuval & Doron, Yotam & Muldal, Alistair & Erez, Tom & Li, Yazhe & Casas, Diego & Budden, David & Abdolmaleki, Abbas & Merel, Josh & Lefrancq, Andrew & Lillicrap, Timothy & Riedmiller, Martin. (2018). DeepMind Control Suite

[2] Lillicrap, T. P., Hunt, J. J., Pritzel, A., Heess, N., Erez, T., Tassa, Y., Silver, D. & Wierstra, D. (2016). Continuous control with deep reinforcement learning.. In Y. Bengio & Y. LeCun (eds.), ICLR, .

