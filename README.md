# INTRODUCTION TO MACHINE LEARNING
# UB CSE574

# Proj 1.1: Software 1.0 versus Software 2.0

The project is to compare two problem solving approaches to software development, the logic based approach (software 1.0) and the machine learning approach (software 2.0). I used the problem of FizzBuzz and trained the neural network with a training set from 10 to 1000 and testing on a test set from 1 to 10.

Result: Making decision on hyper-parameters such as learning rate, number of epochs, loss function(cross-entropy), regularizer. Displayed results in form of graphs

# Proj 1.2: Learning to Rank using Linear Regression

The goal of this project is to use machine learning to solve a problem in information retrieval. Here I trained a linear regression model on LeToR dataset using closed-form solution and stochastic gradient descent (SGD)

Result: Evaluated my solution on a test set using root mean square error

# Proj 2: Finding similarities in hand-writing

The goal of the project is to apply machine learning to solve the handwriting comparison task in forensics using linear regression (gradient descent to train regression model) where I mapped a set of input features to real-value scalar target. CEDAR letter dataset(Human observed and GSC dataset using feature engineering) is used for this project.

Result: Evaluated the solution using Root mean square error and the results are provided as graphs.

# Proj 3: Classification

This project is to implement machine learning methods for the task of classification. I have implemented an ensemble of four classifiers for a given task. The results of the individual classifiers are combined to make a final decision. The dataset used here is MNIST digit images and USPS dataset. The four classifiers applied are logistic regression, multilayer perceptron neural network, Random forest, support vector machine.

Result: Evaluated each solution using classification accuracy, constructed a confusion matrix for each classifier and evaluated the performance of ensemble classfier

# Proj 4: Tom and Jerry in Reinforcement learning

The project combines reinforcement learning and deep learning. The task is to teach the agent to navigate in the grid-world environment. The modeled game is Tom and Jerry cartoon where the agent (Tom) has to find the shortest path to reach Jerry (goal). To solve the problem, I have used deep reinforcement learning algorithm DQN (deep Q-Network)

Result: Implemented Q function and made the agent to move to the goal in shortest way
