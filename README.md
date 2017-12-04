# SudokuSolver
Solve sudoku puzzle taking an image as input. Each digit can be handwritten.
Note: currently the code only supports puzzle images which the largest outliner and the outliner of each 3 * 3 blob are both bold black, and the inliner of each 3 * 3 blob are light black.
Check the manual3.bmp for an example.

## Overview
+ Use OpenCV to locate each unit-blob
+ Use TensorFlow to build a MNIST digit recognizer and recognize the digit in each unit-blob
+ Use dlxsudoku package to solve extracted puzzle

## Python Environment
+ Anaconda 3
+ Python 3.6

## Requirement
+ [OpenCV3](https://anaconda.org/menpo/opencv3)
+ [TensorFlow](https://anaconda.org/conda-forge/tensorflow)
+ [dlxsudoku](https://pypi.python.org/pypi/dlxsudoku)
