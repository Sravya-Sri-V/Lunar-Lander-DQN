**Lunar Lander Deep Q-Learning**__
This repository contains a Deep Q-Learning implementation for the LunarLander-v3 environment using PyTorch and Gymnasium. The agent is trained to control a lunar lander to safely land on a target platform.

**Features**__
Custom neural network architecture for Q-learning.
Experience replay to stabilize training.
Soft update of target Q-network.
Hyperparameter tuning for optimal performance.
Visualization of the trained agent in action.


**Requirements**__

_Install the necessary dependencies:_
pip install torch gymnasium numpy matplotlib imageio
pip install "gymnasium[box2d]" "gymnasium[atari, accept-rom-license]"

_For rendering the environment, ensure you have:_
apt-get install -y swig

_How to Run_
**1. Clone the Repository**
git clone https://github.com/<YourUsername>/lunar-lander-dqn.git
cd lunar-lander-dqn

**3. Open the Notebook**
Launch the Jupyter Notebook to train and visualize the agent:
jupyter notebook lunar_lander_dqn.ipynb

**Repository Structure:**
lunar-lander-dqn/
│
├── lunar_lander_dqn.ipynb     # Jupyter Notebook with training and visualization
├── README.md                  # Project documentation

**Environment Details:**
_Environment Name:_ LunarLander-v3
_State Space:_ 8-dimensional continuous vector.
_Action Space:_ 4 discrete actions:
          Do nothing
          Fire left orientation engine
          Fire main engine
          Fire right orientation engine
          
**Results**__
The agent successfully solves the Lunar Lander environment, achieving an average score of 200+ over 100 episodes after approximately 700 episodes of training.

**Acknowledgments**__
Gymnasium for the Lunar Lander environment.
PyTorch for neural network implementation.
Inspiration from reinforcement learning literature and tutorials.

**Tips for Viewing Jupyter Notebooks**__
GitHub supports rendering .ipynb files directly in the browser. However, for interactive use, it's recommended to open the notebook in a Jupyter environment.
