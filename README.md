# Reggies-Linear-Regression-Fundamental-Python-Project

## Description

Reggie is a mad scientist who has been hired by the local fast food joint to build their newest ball pit in the play area. As such, he is working on researching the bounciness of different balls so as to optimize the pit. He is running an experiment to bounce different sizes of bouncy balls, and then fitting lines to the data points he records. He has heard of linear regression, but needs your help to implement a version of linear regression in Python.

Linear Regression is when you have a group of points on a graph, and you find a line that approximately resembles that group of points. A good Linear Regression algorithm minimizes the error, or the distance from each point to the line. A line with the least error is the line that fits the data the best. We call this a line of best fit.

We will use loops, lists, and arithmetic to create a function that will find a line of best fit when given a set of data.

## Objectives

Reggie wants to try a bunch of different m values and b values and see which line produces the least error. To calculate error between a point and a line, he wants a function called calculate_error(), which will take in m, b, and an [x, y] point called point and return the distance between the line and the point.

To find the distance:


*   Get the x-value from the point and store it in a variable called x_point
*   Get the y-value from the point and store it in a variable called y_point
*   Use get_y() to get the y-value that x_point would be on the line
*   Find the difference between the y from get_y and y_point
*   Return the absolute value of the distance (you can use the built-in function abs() to do this)

The distance represents the error between the line y = m*x + b and the point given.


