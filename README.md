**Humanoid Robot Reinforcement Learning (RL)**
This repository contains code for training a humanoid robot using reinforcement learning (RL) to learn natural walking behaviors. The environment, HumanoidEnv, has been designed to simulate a humanoid robot and provide rewards based on its movements and stability.

**Project Description**
The project aims to create a reinforcement learning agent that can control a humanoid robot to walk in a natural way. The robot’s movement is simulated in a custom environment based on OpenAI's gymnasium framework, and we utilize the PPO (Proximal Policy Optimization) algorithm from stable-baselines3 to train the agent.

**Key Features:**
**Custom Humanoid Environment:** A humanoid robot with various state parameters (e.g., forward velocity, torso height, joint torques) that affect its ability to walk.
**PPO-based RL:** Training the humanoid agent using Proximal Policy Optimization (PPO), a powerful reinforcement learning algorithm.
**Natural Walking Incentive:** The reward function is designed to encourage forward movement while maintaining stability, penalizing backward motion and falls.
**Real-time Rendering:** The environment supports real-time visualization of the humanoid’s actions as it learns to walk.
**TensorBoard Logging:** Training statistics are logged to TensorBoard for monitoring progress
