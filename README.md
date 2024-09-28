# Super Mario Reinforcement Learning (PPO)

This project is a reinforcement learning model designed to teach an agent to play Super Mario using the Proximal Policy Optimization (PPO) algorithm. Inspired by Nicholas' implementation, this version includes fixes to allow RL training without the need for an external display. The environment is built using `gym_super_mario_bros` and `nes_py`.

## Features
- PPO-based RL training for Super Mario
- No external display needed to run the environment
- Saves model weights (`mario_model.pth`) for future use

## Requirements
- Python 3.x
- `gym_super_mario_bros==7.3.0`
- `nes_py`
- `torch` (for handling the model)
- `tqdm` (for progress tracking)

## Installation
To set up the environment and dependencies, run:

```bash
pip install gym_super_mario_bros==7.3.0 nes_py torch tqdm
