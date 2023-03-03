# CS7641 Assignment 2 - Randomized Optimization
The goal of this assignment has 2 parts.
The first is to look at how 4 different algorithms (Randomized Hill Climbing, Simulated Annealing, Genetic Algorithms and MIMIC) work on 3 different optimization problems and compare their strengths and differences.

The second is to replace the standard optimizer for neural network training with 3 randomized optimization algorithms (Randomized Hill Climbing, Simulated Annealing, Genetic Algorithms) and compare them to the baseline. 

# Part 1 - 3 Problems

The 3 optimization problems are:
1) Flip Flop
2) Knapsack Problem
3) One Max

They are chosen to represent a broad range of problems types and range from easy (OneMax) to complex (Knapsack). This will show the different strengths and weaknesses for the different algorithms. 

# Part 2 - Neural Network

For the neural network problem, we will be using this dataset. The .csv of the dataset is included in the repo.
Dataset 1 : Heart Disease Dataset https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

The goal of this part is to replace the standard gradient based optimizer with a non gradient based optimizer and to contrast and see the changes to its performance. 

# Getting Started
For testing, a machine with python>=3.6 needs to be installed as well as the following packages:
pandas, numpy, scikit-learn, matplotlib, mlrose-hiive

# Running
To run the notebook, simply follow the steps.

Download and unzip the folder
Run the ipython notebook. To run simply hit the run all button. To save time, it is recommended to skip the gridsearch phase in order to speed up analysis.


# Addtional Info
The datasets have been uploaded to the repo to make it easy to find. Should you need additional info, links to the dataset have been included at the top

