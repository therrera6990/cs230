# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

We leanred how to apply KMAPs to actual boards to actually visualize what SOP and POS looks like on a board and how we are able to
turn a truth table int oactual outputs. We learned much more about vivado and working with code and test cases.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?

Because the map representes a logical space that is continous which can be visualized as a cylinder so the 
opposite ends are actually adjacent.

### Why are the names Sum of Products and Products of Sums?

Because its based on how boolean logic cates are arranged to define a function
for SOP we use OR gates which are sums and for POS we use AND gates which are products

### Open the test.v file – how are we able to check that the signals match using XOR?

Because we are using test cases that check to see if SOP and POS holds true based on the equations we have inputted
