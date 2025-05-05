# AI_Project
🐍 Deep Q-Learning Snake Game AI
A Deep Reinforcement Learning project that teaches an AI agent to play the classic Snake game using Deep Q-Networks (DQN).

## 🎯 Project Objective
Develop an autonomous agent that learns to play the Snake game intelligently by interacting with the game environment, maximizing rewards, and avoiding failure through Deep Q-Learning.

## 🛠️ Tools & Libraries
1. Python

2. PyTorch – Neural network implementation

3. Pygame – Game environment

4. NumPy – Data handling

5. Matplotlib – Visualizing training metrics

## Rewards
The total reward is calculated for each episode, which is continued for 30 games.
We collect average total reward for every 100 consecutive episodes. The threshold is unknown.
The snake's length and reward increase by 1 each time an apple is eaten.
The reward is reduced by 1 every time the snake collides with itself,
bumps into the border of the board, or if it does not eat an apple for a long time.

![image](https://github.com/user-attachments/assets/ce593a96-6e67-4035-aae4-2710440ed6a2)

## Actions
0 - turn left, 1 - turn right, 2 - move up, 3 - move down

## Snake's Length
For any 100 consecutive episodes we get value 'Avg.LenOfSnake' adn 'Max.LenOfSnake'.

1.For Learning rate = 1e-4, number of episodes = 50000

Avg.LenOfSnake = 18, Max.LenOfSnake = 46

![image](https://github.com/user-attachments/assets/d077ddb9-2f7d-4a23-8865-e48efe81e309)

2.For Learning rate = 1e-5, number of episodes = 60000

Avg.LenOfSnake = 18, Max.LenOfSnake = 44


![image](https://github.com/user-attachments/assets/ff84de50-7618-4ba8-a6c6-2d5e3f3d6453)

## Train
1. For Learning rate = 1e-4, number of episodes = 50000

![image](https://github.com/user-attachments/assets/382c0736-fe05-4c17-a63b-e9e16edb95cf)

![image](https://github.com/user-attachments/assets/72bc0a1a-f7b7-4d09-8693-d04b81eff6a4)

2. For Learning rate = 1e-5, number of episodes = 60000

![image](https://github.com/user-attachments/assets/281d15d6-d948-407f-bb95-60421072e373)

![image](https://github.com/user-attachments/assets/cf3544a3-3cc8-4ecf-a114-525f408cfb00)

## Video

See Video on YouTube https://youtu.be/HclSp0XOKUY






