# Atari-AI
Teach AI to Play Arcade Games in the Atari Gym

<p align="center">
<img src="https://github.com/crypto-code/Atari-AI/blob/master/assets/spacegif.gif" height="500" align="middle" /> 
<img src="https://github.com/crypto-code/Atari-AI/blob/master/assets/ponggif.gif" height="500" align="middle" /> </p>


## Actor Critic Neural Network
It is a method that uses two neural networks to optimize performance. The Actor Network is the AI agent that plays the game while the Critic Network classifies the game as a good or a bad one. 

![](assets/model.png)

For more info go [here](https://www.freecodecamp.org/news/an-intro-to-advantage-actor-critic-methods-lets-play-sonic-the-hedgehog-86d6240171d/).

## Instsallation
Download the entire repositry, pre-trained models are included for SpaceInvaders, Breakout and Pong.
To check list of all possible arguments run
'''
ML~ python game.py --help

usage: game.py [-h] [--env ENV] [--processes PROCESSES] [--render RENDER]
               [--test TEST] [--rnn_steps RNN_STEPS] [--lr LR] [--seed SEED]
               [--gamma GAMMA] [--tau TAU] [--horizon HORIZON]
               [--hidden HIDDEN]

optional arguments:
  -h, --help            show this help message and exit
  --env ENV             gym environment
  --processes PROCESSES
                        number of processes to train with
  --render RENDER       renders the atari environment
  --test TEST           sets lr=0, chooses most likely actions
  --rnn_steps RNN_STEPS
                        steps to train LSTM over
  --lr LR               learning rate
  --seed SEED           seed random # generators (for reproducibility)
  --gamma GAMMA         rewards discount factor
  --tau TAU             generalized advantage estimation discount
  --horizon HORIZON     horizon for running averages
  --hidden HIDDEN       hidden size of GRU

'''
