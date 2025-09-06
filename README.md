# Super Mario Reinforcement Learning Agent 
This project features a Reinforcement Learning (RL) agent trained to autonomously play and master the classic Super Mario Bros. game. The agent is built using the Proximal Policy Optimization (PPO) algorithm and learns optimal policies through interaction with the game environment, facilitated by OpenAI Gym.
#**Key Features**
Custom Game Environment: Built a dedicated game environment using OpenAI Gym and nes_py wrappers, with simplified movement settings for effective agent training.

Advanced Preprocessing: Implemented a robust preprocessing pipeline with stable-baselines3, applying grayscale filters, frame stacking, and vectorization to optimize the agent's learning process.

Stable PPO Implementation: Applied Proximal Policy Optimization (PPO) with custom callbacks to achieve stable and efficient agent learning within just 10,000 interaction steps.

Hyperparameter Tuning: Determined the optimal discount factor for maximizing returns by analyzing recursive Bellman equations through reward and value iterations.

#**Tech Stack**
Python 3.8+

OpenAI Gym: For creating and interacting with the game environment.

Stable-Baselines3: For the high-quality PPO implementation.

PyTorch: As the backend for Stable-Baselines3.

nes-py: For emulating the Nintendo Entertainment System.

OpenCV-Python: For image processing and vectorization.
