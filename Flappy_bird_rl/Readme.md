# Flappy Bird DQN Agent

Deep Q-Network (DQN) se Flappy Bird khud khelna seekhta hai. Built with PyTorch and Gymnasium.

## Files
- `agent.py`: training aur play (main file)
- `dqn.py`: neural network (AI ka dimaag)
- `experience_replay.py`: replay memory (AI ki yaadash)
- `game_flappy_bird.py`: game ko manually khelke test karna
- `parameters.yaml`: hyperparameters (epsilon, gamma, learning rate, etc.)
- `runs/`: trained model (`.pt`) aur training log

## Requirements
pip install torch gymnasium flappy-bird-gymnasium pyyaml

## How to run
Train karne ke liye:
python agent.py flappybirdv0 --train

Trained model se khelke dekhne ke liye:
python agent.py flappybirdv0
