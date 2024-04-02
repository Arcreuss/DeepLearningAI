# DeepLearningAI
 UE5.3 : AI Cars learns to drive with DeepLearning methods

#DeepLearning AI 1.0: Simple neural network

##Deep Learning
Deep Learning: Simple neural network without hidden layers

##AI Cars: 
There are ± 30 cars on the track.
The cars have 5 points of vision to enable them to turn.

##Time: 
Race time: ± 60 seconds, timer common to AIs. 

##Reward system: 
When a car passes a checkpoint, it gains 1 second on its timer to encourage it to make more points.
In addition, a coefficient will be applied to checkpoints throughout the circuit to improve the AI's score as it improves.

##Generation:
The first generation has a random weight.
The next generation focuses on the top 5 AIs. This means that generation n+1 will generate new AI cars with the old best data cars.
The more points a car has, the more data the next generation will get.
