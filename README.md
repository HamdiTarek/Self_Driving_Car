"# Self_Driving_Car" 
Self-driving cars represent one of the most significant advances in modern history. Their impact will go beyond technology, beyond transportation, beyond urban planning to change our daily lives in ways we have yet to imagine.
Using Udacity's environment as car simulator app to create a self-driving car ! 
We used Keras to train a convolutional neural network on images from the car's cameras as well as steering angles from human driving. Using just those 2 data points, it'll be able to drive itself on any road. 
More you train the car more you will get good result.
Files : 
We're going to use Udacity's self driving car simulator as a testbed for training an autonomous car : https://github.com/udacity/self-driving-car-sim

Dependencies
You can install all dependencies by running one of the following commands

You need a anaconda or miniconda to use the environment setting.

# Use TensorFlow without GPU
conda env create -f environments.yml 

# Use TensorFlow with GPU
conda env create -f environment-gpu.yml

# COMMANDS

1/  conda env create -f D:\Self_Driving_Car\How_to_simulate_a_self_driving_car-master\environments.yml 

2/ activate car-behavioral-cloning

3/ python D:\Self_Driving_Car\How_to_simulate_a_self_driving_car-master\model.py

4/ python D:\Self_Driving_Car\How_to_simulate_a_self_driving_car-master\drive.py D:\Self_Driving_Car\How_to_simulate_a_self_driving_car-master\model.h5
