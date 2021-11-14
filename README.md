# n-queens-algorithms
This repository contains implementations of some famous algorithms for the n-queens problem.

# How to Run
Very simple, just use python and run one of the scripts that you need.

## Output of Steepest Ascent Hill-Climbing Algorithm
```
$ python n_queen_steepest_ascent.py
```
```
Number of episodes: 10
Number of successful episodes: 3
Average step per successful episode: 3.6666666666666665
Number of unsuccessful episodes: 7
Average step per unsuccessful episode: 2.5714285714285716
[[0 1 0 0 0 0 0 0]
 [0 0 0 0 0 0 1 0]
 [0 0 0 0 1 0 0 0]
 [0 0 0 0 0 0 0 1]
 [1 0 0 0 0 0 0 0]
 [0 0 0 1 0 0 0 0]
 [0 0 0 0 0 1 0 0]
 [0 0 1 0 0 0 0 0]]
[[0 1 0 0 0 0 0 0]
 [0 0 0 0 0 1 0 0]
 [1 0 0 0 0 0 0 0]
 [0 0 0 0 0 0 1 0]
 [0 0 0 1 0 0 0 0]
 [0 0 0 0 0 0 0 1]
 [0 0 1 0 0 0 0 0]
 [0 0 0 0 1 0 0 0]]
[[0 1 0 0 0 0 0 0]
 [0 0 0 1 0 0 0 0]
 [0 0 0 0 0 1 0 0]
 [0 0 0 0 0 0 0 1]
 [0 0 1 0 0 0 0 0]
 [1 0 0 0 0 0 0 0]
 [0 0 0 0 0 0 1 0]
 [0 0 0 0 1 0 0 0]]
```
## Output of Stochastic Hill-Climbing Algorithm
```
$ python n_queen_stochastic.py
```
```
Number of episodes: 10
Number of successful episodes: 1
Average step per successful episode: 7.0
Number of unsuccessful episodes: 9
Average step per unsuccessful episode: 4.555555555555555
[[0 0 0 0 1 0 0 0]
 [1 0 0 0 0 0 0 0]
 [0 0 0 0 0 0 0 1]
 [0 0 0 1 0 0 0 0]
 [0 1 0 0 0 0 0 0]
 [0 0 0 0 0 0 1 0]
 [0 0 1 0 0 0 0 0]
 [0 0 0 0 0 1 0 0]]
```
