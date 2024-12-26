# **Nesterov’s Accelerated Gradient Descent for Convex Programming**
## **Overview**

This project explores the implementation and analysis of Nesterov’s Accelerated Gradient Descent, an advanced optimization algorithm introduced in 1983. Designed to tackle convex programming problems, this method significantly improves convergence rates compared to traditional gradient descent, setting a new standard in optimization techniques.
## **Features**
### **1. Insights from the Paper**

    Achieves a superior convergence rate of O(1/k2)O(1/k2), far surpassing conventional methods.
    Introduces non-monotonic function adjustments, enhancing the algorithm's ability to escape local minima.
    Reduces computational effort by optimizing gradient and function evaluations, making it more efficient for large-scale problems.

### **2. Algorithm Implementation**

    Implemented Nesterov’s Accelerated Gradient Descent and compared it against traditional gradient descent on logistic loss.
    Utilized both a custom implementation and the CVXPY library to ensure accuracy and reliability.

### **3. Applications**

    Solves optimization challenges in convex sets and functions, with direct applications in machine learning and operations research.
    Tackles extreme value problems formulated within minimax frameworks, extending the algorithm’s practical relevance.

## **Results**

    Successfully validated the algorithm’s efficiency, demonstrating its faster convergence and reduced computational cost.
    Highlighted its capability to serve as a foundational technique for advanced optimization algorithms.

## **References**

    Nesterov, Yurii. "A method for solving the convex programming problem with convergence rate O(1/k2)O(1/k2)." (1983).
