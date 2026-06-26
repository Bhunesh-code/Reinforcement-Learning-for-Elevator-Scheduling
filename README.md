# Reinforcement Learning for Elevator Dispatch Scheduling 
> **MSc Data Science & Analytics Dissertation** | University College Cork

An advanced computational framework designed to optimize real-time vertical transportation asset allocation under stochastic passenger transit loads. This project builds a custom simulation environment to benchmark deep reinforcement learning agents against traditional heuristic and classic tabular architectures.

---

##  Key Highlights & Frameworks
* **Algorithms Evaluated:** Deep Q-Networks (DQN), Proximal Policy Optimization (PPO), and Tabular Q-Learning.
* **Core Goal:** Minimize passenger wait time distributions and average queue lengths during peak traffic hours.
* **Tech Stack:** `Python`, `Stable-Baselines3`, `Gymnasium (OpenAI Gym)`, `Pandas`, `NumPy`, `Matplotlib`.

---

##  Repository Structure
```text
├── data/
│   ├── training_metrics_dqn.csv      # Captured performance loops for DQN agent
│   ├── training_metrics_ppo.csv      # Captured performance loops for PPO agent
│   └── training_metrics_qlearn.csv   # Captured performance loops for Q-Learning agent
├── RL for Reinforcement Learning Code.ipynb  # Core execution, model architectures, and training loops
└── README.md                         # Project documentation
