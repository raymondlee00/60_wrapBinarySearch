# 60_wrapBinarySearch

**y=log(x)**
In terms of algorithmic analysis, the logarithm function measures the time (y) at which an algorithm can complete an x-sized task. This function means that the time that the algorithm takes to complete a task scales with how many times that task can be halved.

The graph looks like this:
![alt text](logbase2.PNG)

# Recursive Solution
  0. Create a search algorithm to find a target element in a sorted array
  1. Given the task to find an element in a sorted array, the recursive abstraction can find the element in half the sorted array.
  2. i. Does the current element equal the target element? <br />
     ii. If the length of the array is 0, return -1. If the length of the array is 1, return the first element. <br />
     iii. a. combine... <br />
          b. the result of the recursive abstraction applied to half of the array with... <br />
          c. ???
