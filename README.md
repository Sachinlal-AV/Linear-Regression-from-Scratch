
# Linear Regression from scratch

This assignment was part of the course ED-5430, Data Science:Theory and Practice, which was part of my course work. The main objective of the assignment was to implement the linear regression on a small data set without using any scikit learn libraries.


## Lessons Learned

I have learned how to implement a linear regression model without using any standard libraries. Here we have implemented the exhaustive search method for optimizing the learning parameter (alpha), that is usually taken as 0.1 or 0.01.The learning parameter was bracketed between a minimum and maximum value using this method, further Newton-Raphson method was employed to find the critical value of learning parameter that can be finally used for the gradient descent algorithm. At the end of the assignment, we ploted the best fit line for the given data using the weights found out from employing the steepest gradient decent algorithm and also ploted the cost function and contour of the cost function with optimum weights.
