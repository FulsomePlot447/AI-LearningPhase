# 🤖 Reinforcement Learning with Gymnasium & Stable-Baselines3

A hands-on collection of notebooks exploring the fundamentals and practical implementation of **Reinforcement Learning (RL)** using modern Python libraries such as **Gymnasium** and **Stable-Baselines3**. This repository covers everything from classical tabular methods like **Q-Learning** to deep reinforcement learning algorithms including **DQN**, **A2C**, and **Policy Gradient** methods.

Whether you're just getting started with RL or looking to understand modern agent-based learning, these notebooks provide step-by-step implementations and explanations.

---

# 📂 Repository Structure

```text
├── notebooks/
│   ├── 01_A2C.ipynb
│   ├── 02_deep-q.ipynb
│   ├── 03_policy_gradient.ipynb
│   ├── 04_q-learning.ipynb
│   ├── 05_rocket_land.ipynb
│
├── models/
│
└── README.md
```

---

# 📖 Notebook Overview

## 1. Gymnasium Fundamentals

Learn the basics of reinforcement learning environments using **Gymnasium**, the maintained successor to OpenAI Gym.

### Topics Covered

* RL environment structure
* Observation space
* Action space
* Episodes and timesteps
* Reset and step functions
* Rendering environments
* Reward signals
* Environment wrappers

**Skills Learned**

* Understanding RL environments
* Agent-environment interaction
* Running simulations
* Custom environment exploration

---

## 2. Stable-Baselines3

Learn how to quickly train reinforcement learning agents using the Stable-Baselines3 library.

### Topics Covered

* Installing Stable-Baselines3
* Creating environments
* Training agents
* Saving and loading models
* Evaluating trained policies
* TensorBoard integration

Supported algorithms include:

* PPO
* A2C
* DQN
* SAC (if applicable)
* TD3 (if applicable)

**Skills Learned**

* Modern RL workflows
* Model persistence
* Policy evaluation
* Benchmarking agents

---

## 3. Q-Learning (Q-Table)

Implement the classical tabular reinforcement learning algorithm.

### Topics Covered

* Q-Table initialization
* Bellman Equation
* Exploration vs Exploitation
* ε-Greedy strategy
* Updating Q-values
* Policy extraction

**Skills Learned**

* Tabular reinforcement learning
* Value-based learning
* Dynamic programming intuition
* Learning optimal policies

---

## 4. Deep Q Network (DQN)

Move beyond tabular methods by approximating Q-values with neural networks.

### Topics Covered

* Deep Q Networks
* Neural network function approximation
* Experience Replay
* Target Networks
* Mini-batch learning
* Model optimization

**Skills Learned**

* Deep Reinforcement Learning
* Neural network-based agents
* Stable training techniques
* Large state-space handling

---

## 5. Advantage Actor-Critic (A2C)

Learn one of the most widely used Actor-Critic algorithms.

### Topics Covered

* Actor-Critic architecture
* Policy network
* Value network
* Advantage estimation
* On-policy learning
* Parallel environments (if applicable)

**Skills Learned**

* Policy optimization
* Actor-Critic methods
* Value estimation
* Efficient RL training

---

## 6. Policy Gradient Methods

Explore reinforcement learning algorithms that optimize policies directly.

### Topics Covered

* Policy gradients
* REINFORCE algorithm
* Discounted rewards
* Monte Carlo estimation
* Gradient ascent
* Stochastic policies

**Skills Learned**

* Direct policy optimization
* Probabilistic action selection
* Reward maximization
* Gradient-based RL

---

## 7. Hyperparameter Tuning

Understand how hyperparameters impact reinforcement learning performance.

### Topics Covered

* Learning rate
* Discount factor (γ)
* Exploration rate (ε)
* Batch size
* Replay buffer size
* Number of training steps
* Target network update frequency
* Entropy coefficient
* Evaluation metrics

**Skills Learned**

* Hyperparameter optimization
* Training stability
* Performance comparison
* Efficient experimentation

---

# 🛠 Technologies Used

* Python
* Gymnasium
* Stable-Baselines3
* PyTorch
* NumPy
* Matplotlib
* TensorBoard
* Jupyter Notebook

---

# 🎯 Learning Outcomes

By completing these notebooks, you'll gain practical experience with:

* Reinforcement Learning fundamentals
* Markov Decision Processes (MDPs)
* Agent-environment interaction
* Value-based learning
* Policy-based learning
* Actor-Critic methods
* Deep Reinforcement Learning
* Hyperparameter tuning
* Model evaluation
* Experiment tracking
* Training intelligent agents

---

# 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/FulsomePlot447/AI-LearningPhase.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the notebooks in sequence to progressively build your understanding of reinforcement learning.

---

# 📚 Prerequisites

To get the most out of this repository, you should have a basic understanding of:

* Python programming
* NumPy
* Linear Algebra
* Probability
* Calculus (helpful but not mandatory)
* Machine Learning fundamentals
* PyTorch basics

---

# 📌 Note

Some reinforcement learning algorithms may require extended training time depending on the selected environment and available hardware. For faster experimentation, GPU acceleration is recommended for deep reinforcement learning algorithms such as DQN and A2C.

---

## ⭐ If you find this repository useful, consider giving it a star!

