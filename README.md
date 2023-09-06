
# DQN Agent for Space Invaders

## Description:
This personal project explores the implementation of a Deep Q-Network (DQN) agent to play the classic Atari game, "Space Invaders". Using the OpenAI Gym environment, the agent's primary goal is to maximize its cumulative reward by effectively shooting aliens and avoiding their counterattacks.

## Deep Learning Methods Employed:
1. **Deep Q-Networks (DQN):** This method employs neural networks to approximate the Q-values. It significantly extends the capabilities of traditional Q-learning by handling vast state spaces like those in Atari games.
2. **Experience Replay:** To break the correlation between sequential experiences and stabilize the learning process, experiences are stored in a replay buffer. Random samples from this buffer are used for training.
3. **Frame Stacking:** Multiple frames are stacked together to provide the agent with a sense of motion. This is crucial for games where understanding the trajectory of moving objects (like bullets or aliens) can influence the decision-making process.
4. **Reward Engineering:** Rewards are carefully designed to guide the agent towards optimal gameplay. For example, the agent receives positive rewards for shooting aliens and negative rewards for getting hit.

## Benefits of the Methods:
1. **DQN:** Allows the agent to handle high-dimensional state spaces and learn complex strategies that would be infeasible with traditional Q-learning.
2. **Experience Replay:** Enhances the stability of the learning process by reusing past experiences, ensuring diverse and uncorrelated training samples.
3. **Frame Stacking:** Provides the agent with temporal information, essential for making decisions based on the movement of game elements.
4. **Reward Engineering:** Directs the agent towards desired behaviors, ensuring it learns to prioritize actions that maximize its score.

## Further Insights:
Throughout the project, various parameters and strategies were experimented with to optimize the agent's performance. This involved tweaking the neural network architecture, adjusting reward structures, and experimenting with different frame sizes and stacking strategies.

For anyone keen on diving deep into reinforcement learning and game agents, this project serves as an enlightening journey into the intricacies of DQN and its associated techniques.
