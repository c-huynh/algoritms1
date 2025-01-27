# Homework 6

## Median Maintenance Algorithm

The goal of this problem is to implement the "Median Maintenance" algorithm
(covered in the Week 5 lecture on heap applications). The text file contains a
list of the integers from 1 to 10000 in unsorted order; you should treat this as
a stream of numbers, arriving one by one. Letting xi denote the ith number of the
file, the kth median mk is defined as the median of the numbers x1,..., xk. (So,
if k is odd, then mk is ((k + 1) / 2)th smallest number among x1,..., xk; if k 
is even, then mk is the (k / 2)th smallest number among x1,..., xk.)

In the box below you should type the sum of these 10000 medians, modulo 10000
(i.e., only the last 4 digits). That is, you should compute:

(m1 + ... + m10000)mod10000

OPTIONAL EXERCISE: Compare the performance achieved by heap-based and
search-tree-based implementations of the algorithm.

`python medians.py`

*answer = 1213*

## 2-Sum Algorithm

The goal of this problem is to implement a variant of the 2-SUM algorithm
(covered in the Week 6 lecture on hash table applications).

The file contains 1 million integers, both positive and negative (there might be
some repetitions!).This is your array of integers, with the ith row of the file
specifying the ith entry of the array.

Your task is to compute the number of target values t in the interval [-10000,10000] (inclusive) such that there are distinct numbers x, y in the input
file that satisfy x + y = t.

(NOTE: ensuring distinctness requires a one-line addition to the algorithm from lecture.)

`python two_sum.py`

*answer = 427*