# AI_atari_games
--- 
## Overview

A Tensorflow DQN implementation based on [DeepMind's DQN](https://storage.googleapis.com/deepmind-data/assets/papers/DeepMindNature14236Paper.pdf) for playing Atari games.This the code for 'Build a game AI'


## Dependencies
- [gym](https://gym.openai.com)
- [Tensorflow](https://www.tensorflow.org)
- [virtualenv] (https://virtualenv.pypa.io/en/latest/installation.html)
- or [Anaconda] (https://www.continuum.io/downloads)
 
## Basic Usage
To run, type the following into terminal

`python atari.py --game <env_name>`

However if you are on an Anaconda virtual environment no need to type <env_name> just type 

`python atari.py --game SpaceInvaders-v0 --display true`

## Credits
Credit for the vast majority of code here goes to Kee Hyun Won.  I just adjusted the code for my environment and the new 
tensorflow deprecated variables.

