# pong_neural_network

##Overview
I have build
the game of Ping Pong (http://www.ponggame.org) from scratch. Then I build a [Deep Q Network](https://www.quora.com/Artificial-Intelligence-What-is-an-intuitive-explanation-of-how-deep-Q-networks-DQN-work) that gets better and better over time through trial and error. The DQN is a convolutional neural network that reads in pixel data from the game and the game score. Using just those 2 parameters, it learns what moves it needs to make to become better.

##Installation


* tensorflow
* cv2
* numpy
* random
* collections
* pygame

use [pip](https://pypi.python.org/pypi/pip) to install the dependencies. Tensorflow and cv2 are more manual. Links provided above ^

##Usage 

Run it like this in terminal. The longer you let it run, the better it will get.

```
python RL.py
```

##Reference

 [malreddysid](https://github.com/malreddysid)

