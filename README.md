# reinforce-safe_exploration-gridworld
Project for EEL-6935 Safe Autonomous System Graduate Coursework at ECE, University of Florida.

The objective is to solve the safe exploration problem in a reinforcement learning framework in the Island Navigation Environment, one of the RL environments proposed by OpenAI[1]. We define dangerous states as states from where agents can go to catastrophic states within a short period and propose to distinguish between safe and dangerous states by training a separate supervised neural network. This network will be trained whenever a catastrophe
is detected. In subsequent exploration, we reduce the reward obtained in dangerous states thereby motivating the agent to avoid those states and thereby avoid catastrophe. The proposed approach was used to modify the Advantage Actor-Critic RL algorithm. Experiment results suggest improvement over the base
A2C algorithm in terms of reducing catastrophic events and faster convergence as well.

[1] J. Leike, M. Martic, V. Krakovna, P. A. Ortega, T. Everitt, A. Lefrancq, L. Orseau, and S. Legg, “AI safety grid-worlds,” CoRR, vol. abs/1711.09883, 2017. [Online]. Available: http://arxiv.org/abs/1711.09883.

Requred Modules: pytorch & numpy

Just run the notebook.
