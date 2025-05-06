# CSE374-Coding-Assignment-05

Download Here: [CSE374 Coding Assignment 05](https://codingherolab.com/product/cse374-coding-assignment-05/)

For Custom/Original Work email codingprolab@gmail.com/whatsapp +1(541)423-7793

Greedy is an algorithmic paradigm that builds up a solution piece by piece, always choosing the
next piece that offers the most obvious and immediate benefit. Greedy algorithms are used for
optimization problems. An optimization problem can be solved using Greedy if the problem has
the following property: At every step, we can make a choice that looks best at the moment, and
we get the optimal solution of the complete problem.
Problem Statement
You are given n activities with their start and finish times. Select the maximum number of
activities that can be performed by a single person, assuming that a person can only work on a
single activity at a time.
The greedy choice is to always pick the next activity whose finish time is least among the
remaining activities and the start time is more than or equal to the finish time of previously
selected activity.
Test Cases
start[] = {1, 3, 0, 5, 8, 5};
finish[] = {2, 4, 6, 7, 9, 9};
-> Should select activities 0, 1, 3, and 4 as optimal
start[] = {10, 12, 30};
finish[] = {20, 25, 30};
-> Should select activities 0 and 2
