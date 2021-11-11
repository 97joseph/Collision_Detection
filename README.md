# Collision_Detection

Collision avoidance structure algorithm

Purpose
The purpose of this project is to familiarize you with neural networks and their applications.
More specifically, you will learn to collect training data for a robotics task and, in turn, design a
neural network that can process this data. In the assignment your goal is to help a small robot
navigate a simulated environment without any collisions. To accomplish this, you will need to
train a neural network using backpropagation that predicts whether the robot is going to collide
with any walls or objects in the next time step. All of the theories and best-practices introduced
in the class are applicable here. Your task is to make sure the little fellow can safely explore its
environment!

## Objectives


● Collect and manage a dataset used to train and test a neural network.
● Define and use PyTorch DataLoaders to manage a PyTorch Datasets.
● Design your own neural network architecture in PyTorch.
● Evaluate and improve a neural network model and verify an application in simulation.
Technology Requirements
● System designed for use with Ubuntu 18.04
● Python and its related libraries. Using Anaconda is recommended.
● Python libraries: cython matplotlib sklearn scipy pymunk pygame pillow numpy noise
torch
Project Description
Part 1
The first task is to collect data that can be used to train the model. Collect a single sample per
action containing, in order, the 5 distance sensor readings, the action, and whether or not a
collision occurred (0: no collision, 1: collision). This data should be saved as a .csv file with 7
untitled columns. For grading purposes, submit your ‘submission.csv’ containing 100 data
samples. For training in the future parts, you will need to collect much more than this.
