# flappy-learning
A simple flappy bird game with a reinforcement learning agent.

## Background
This was a project I did back in 2016 during my time in the Univesity of
Pittsburgh Computer Science Masters program in my Fundamentals of Artificial
Intelligence class. I've sinced updated the code to work with the latest version of Python. The goal was to create a reinforcement learning algorithm
that could learn to play Flappy Bird. The algo is trained using a Q-learning
algorithm and can score 1000+ after a few hours of training.

## Setup
To run this code, you will need to have Python 3.x installed on your machine.
You will also need to install the following dependencies:
- `pygame` - for the game environment
- `numpy` - for numerical computations

I recommend creating a virtual environment to run this code. You can do this by
running the following commands in your terminal:

```bash
# Create a virtual environment
python3 -m venv .venv
# Activate the virtual environment
source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
# Install the required dependencies
pip install pygame numpy
```

## Credits
Original game code from
https://github.com/TimoWilken/flappy-bird-pygame/blob/master/flappybird.py
