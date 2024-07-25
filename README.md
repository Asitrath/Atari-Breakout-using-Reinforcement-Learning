# Atari Breakout using Reinforcement Learning

This project implements a Deep Q-Network (DQN) to play Atari Breakout using reinforcement learning techniques.

## Features

- Custom environment wrapper for Atari Breakout
- Deep Q-Network (DQN) implementation with PyTorch
- Epsilon-greedy exploration strategy
- Experience replay for improved learning stability
- Live plotting of training progress

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/Atari-Breakout-using-Reinforcement-Learning.git
   ```
2. Install the required dependencies:
   ```
   pip install gym numpy pillow torch matplotlib opencv-python
   ```

## Usage

To train the agent:
```
python test.py
```

## Project Structure

- `test.py`: Main script to run the training or testing of the agent
- `agent.py`: Implements the DQN agent with replay memory
- `breakout.py`: Custom environment wrapper for Atari Breakout
- `model.py`: Neural network architecture for the DQN
- `plot.py`: Live plotting functionality for training progress

## Technologies Used

- Python
- PyTorch
- OpenAI Gym
- NumPy
- Matplotlib
- OpenCV

## Results

The agent learns to play Atari Breakout through trial and error. Training progress can be monitored through the live plot generated during training.

![Recording 2024-07-25 at 18 51 42](https://github.com/user-attachments/assets/156d0d44-e2f7-4559-94bf-cfe4646755d6)



## Future Work

- Implement prioritized experience replay
- Add support for other Atari games
- Experiment with different neural network architectures

## Contributors


## License

[Choose an appropriate license and add it here]
```

This README provides an overview of your project, instructions for installation and usage, and details about the project structure and technologies used. You may want to customize it further based on any specific details or results from your implementation.
