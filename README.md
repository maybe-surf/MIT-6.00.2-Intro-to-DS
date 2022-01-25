# MIT-6.00.2-Intro-to-DS
*Some code from MIT 6.00.2 [Intro to Data Science](https://www.edx.org/course/introduction-to-computational-thinking-and-data-4) that I took on [edX](https://www.edx.org/) in spring 2021.* 

*Contains mostly the problem sets solutions.*

## Problem Set 1 (PS1)

*Optimization, knapsack problem, decision trees and dynamic programming.* 

**A little context for the problem set 1** (more can be found in the code comments)

>A colony of Aucks (super-intelligent alien bioengineers) has landed on Earth and has created new species of farm animals! The Aucks are performing their experiments on Earth, and plan on transporting the mutant animals back to their home planet of Aurock. In this problem set, you will implement algorithms to figure out how the aliens should shuttle their experimental animals back across space.

Basically this means how would you empty the set of objects of different weight if you can only take a limited weight at at time. 
Tries to find the most efficient (fastest) way to do it.

**ps1_partition.py** contains a generator helper function that generates all possible partitions of a set

**ps1.py** contains the greedy approach, and the brute force algorithm

**ps1_cow_data.txt** contains some basic data about the objects in a set

## Problem Set 2 (PS2)

*Plotting, stochastic thinking, random walks*

**Context for the problem set 2** (more details are in the code comments)

>iRobot is a company (started by MIT alumni and faculty) that sells the Roomba vacuuming robot (watch one of the product videos to see these robots in action). Roomba robots move around the floor, cleaning the area they pass over.

>In this problem set, you will code a simulation to compare how much time a group of Roomba-like robots will take to clean the floor of a room using two different strategies.

>The following simplified model of a single robot moving in a square 5x5 room should give you some intuition about the system we are simulating.

>The robot starts out at some random position in the room, and with a random direction of motion. The illustrations below show the robot's position (indicated by a black dot) as well as its direction (indicated by the direction of the red arrowhead).

>![2022-01-25](https://user-images.githubusercontent.com/97697560/151075747-2e01d3e3-2235-4c9a-aee7-be9e02d00b60.png)

**ps2.py** contains the solution
