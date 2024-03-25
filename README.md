# CS772-project
CS772 Project Proposal - 23/24 II
4/2/2024
Project:
Machine Unlearning 
Seed paper:
Repairing Neural Networks by Leaving the Right Past Behind
Proposed Project Objectives: 

In this paper, we talk about correcting our model after testing. This involves the following ideas:-
First, identifying which points in training are resulting in bad performance on test
Correcting our model by unlearning these points' contributions.


First, we'll use this repair algorithm for various scenarios, including elastic weight consolidation and linear influence function. We will test it on the MNIST and CIFAR-10 datasets and verify the results reported in the research, which compares improvements across several models. EWC influence is the most effective technique for identifying harmful points.

Emphasizing commonly used probability distributions and skillfully estimating adjusted distributions after deleting specific data points is an important method for moving forward in this field. It is also critical to quickly identify data items that need to be eliminated. To improve present methods, we intend to eliminate computationally demanding operations, such as 
integrations, for some commonly used probability distributions in favor of approximate closed-form solutions.
Group Members:
Advait Vashi - 200058
Aryan Vora - 200204
Harsh Trivedi - 200422
Sunreet Khanna - 201020
Tejas Ramakrishnan - 201050 
