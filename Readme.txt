This code used the Pacman framework provided by UC Berkeley. I've modified the feature extraction code in order to enable the pacman eat ghosts when it uses a power pellet.  

The learning algorithm used is On-policy Expected Sarsa

In this project, you will implement value iteration and Q-learning. You will test your agents first on Gridworld (from class), then apply them to a simulated robot controller (Crawler) and Pacman.

Some sample scenarios to try with are:

$ python gridworld.py -a q -k 100 
$ python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 60 -l mediumGrid
$ python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 60 -l mediumClassic


All the interesting code is in qlearningAgents.py and featureExtractors.py.
