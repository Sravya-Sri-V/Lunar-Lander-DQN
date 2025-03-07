**Lunar Lander Deep Q-Learning**

This repository contains a Deep Q-Learning implementation for the LunarLander-v3 environment using PyTorch and Gymnasium. The agent is trained to control a lunar lander to safely land on a target platform.

**Features:**

Custom neural network architecture for Q-learning.
Experience replay to stabilize training.
Soft update of target Q-network.
Hyperparameter tuning for optimal performance.
Visualization of the trained agent in action.


**Requirements:**

**_Install the necessary dependencies:_**

          pip install torch gymnasium numpy matplotlib imageio
          
          pip install "gymnasium[box2d]" "gymnasium[atari, accept-rom-license]"

**_For rendering the environment, ensure you have:_**

          apt-get install -y swig


**_How to Run_**

**1. Clone the Repository:**

          git clone https://github.com/<YourUsername>/Lunar_Lander_DQN.git
          
          cd Lunar_Lander_DQN

**3. Open the Notebook**

Launch the Jupyter Notebook to train and visualize the agent:
jupyter notebook lunar_lander_DQN.ipynb

**Repository Structure:**

Lunar_Lander_DQN/


├── Deep_Q_Learning_For_Lunar_Landing.ipynb     # Jupyter Notebook with training and visualization

├── README.md                  # Project documentation

**Environment Details:**

_Environment Name:_ LunarLander-v3

_State Space:_ 8-dimensional continuous vector.

_Action Space:_ 4 discrete actions:

1.Do nothing

2.Fire left orientation engine

3.Fire main engine

4.Fire right orientation engine
          
**Results:**

The agent successfully solves the Lunar Lander environment, achieving an average score of 200+ over 100 episodes after approximately 700 episodes of training.

**Acknowledgments:**

Gymnasium for the Lunar Lander environment.
PyTorch for neural network implementation.
Inspiration from reinforcement learning literature and tutorials.

**Tips for Viewing Jupyter Notebooks:**

GitHub supports rendering .ipynb files directly in the browser. However, for interactive use, it's recommended to open the notebook in a Jupyter environment.
