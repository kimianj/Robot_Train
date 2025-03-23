# Robot_Train

**This document only includes the initial plan and board map that will be used. Throughout the project, all results and improvements will be thoroughly documented.**

**Getting Started**

This project aims to develop an intelligent robotic arm control system using advanced machine learning techniques. In robotics, machine learning can significantly enhance performance by enabling robots to adapt and optimize their actions. Specifically, this project will focus on training a simulated robotic arm to perform a precise reaching task in a PyBullet environment, where the arm must reach dynamically changing target positions

To achieve this, I will employ Reinforcement Learning (RL), following the Markov Decision Process framework (actions, states, rewards, environment). The training process will begin with a baseline model and progressively incorporate advanced techniques. The robotic arm will have 5 Degrees of Freedom (DoFs), requiring the RL agent to learn complex joint coordination across spherical, prismatic, and other joint types.
  
I am going to follow these steps to ensure the creation of the best model: 
<ul>
  <li>Baseline Model Training</li>
  --> Actions,
  Step,
  Reward,
  Environment,
<li>Neural Network Architecture Exploration</li>
<li>Reward Function Refinement</li>
<li>Hyperparameter Optimization</li>
<li>Visualization Integration</li>
</ul>


My plan right now is to use industry-known libraries such as: 
<ul>
<li>gymnasium(OpenAI)</li>
<li>Stable Baselines3</li>
<li>PyBullet</li>
<li>TensorFlow</li>
<li>PyTorch</li>
<li>NumPy </li>
<li>TensorBoard</li>
</ul>
<br>

**Citation(s):**

Nahavandi, S., Alizadehsani, R., Nahavandi, D., Lim, C. P., Kelly, K., & Bello, F. (2021). Machine learning meets advanced robotic manipulation. Current Opinion in Systems Biology, 27, 100362. https://doi.org/10.1016/j.coisb.2021.100362
