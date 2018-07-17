The README describes the the project environment details (i.e., the state and action spaces, how reward is decided, and when the environment is considered solved).

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas. 

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.


The README has instructions for installing dependencies or downloading needed files.


Navigate to the `p1_navigation_v3/` folder, and run the command below to obtain the required packages.
  ```
  pip3 install -r requirements.txt
  ```


The README describes how to run the code in the repository, to train the agent.

Follow the instructions in `Navigation.ipynb` to get started with training the agent!  To use a Jupyter notebook, run the following command from the `p1_navigation_v3/` folder:
```
jupyter notebook
```

