[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Report about Project 1: Navigation

### Neural Network for Agent learning

For this project, It has been used a standard neural network, made of 2 hidden layers. The architecture adopted is the following:

Input layer: 37
fully connected layer: units=64
activation: ReLU
fully connected layer: units=64
activation: ReLU
Output fully connected: 4

The hyperparameters are the following:

max episodes=5000
max steps=1000
eps start=1.0
eps end=0.01
eps decay=0.995

The training has run with these results:

Episode 100	Average Score: 1.12
Episode 200	Average Score: 4.88
Episode 300	Average Score: 8.34
Episode 400	Average Score: 10.43
Episode 487	Average Score: 13.03

Environment solved in 387 episodes!	Average Score: 13.03

With this progress:

[alt text](https://raw.githubusercontent.com/username/projectname/branch/path/to/running.png)

The Agent before training run as in this video:

![untrained Agent][untrained]

After Training, the agent runs as follows:

![Trained Agent][trained]



