# teamMJJER
##Topic: Stochastic Gradient Descent

###I. Overall Learning Objectives:

Goal: Our assignment will provide students with the foundations of gradient descent with a primary focus on stochastic gradient descent (SGD). In the coding assignment, students will implement and explore various properties of SGD (learning rate, batch size) and its performance on various loss functions. They will work with real data to practice their technical skills and to motivate variations to explore in different situations. Additionally, they will be introduced to variations on the gradient descent algorithm.

1. Multivariable Calculus Review
- Define multivariable concepts (for review) 
- Gradients
- Saddle Points, Local/Global Maxima/Minima

2. Introduction to Gradient Descent
- Establish graphical intuition/visualizations of reg GD
- Define different parameters and discuss how to tune them
- Learning Rate (Explore different behaviors of convergence)
- Introduce Batch gradient descent, mini-batch)

3. Stochastic Gradient Descent (include visualization of SGD) (Emily)
- SGD: Explanation and Motivation, why it is necessary
- Pros and Cons of SGD
- Briefly establish bounds on convergence
- Show this by demonstrating exponential convergence for step sizes within a certain range/ divergence for step sizes that are too large

4. Teach students how to implement SGD in sklearn, using built in functions and compare with student implementation
- Introduction to sklearn (relevant methods used in practice)
- Quick recap of jupyter notebook
- Guide student through manual implementation of SGD

5. Show students examples of how SGD performs based on different loss functions:
- Examples of loss functions with saddle points, local minima versus global minima
- Explore different loss functions 
- When to use certain loss functions? (Squared-Loss, L2 regularization, logistic loss)
- Ask them to compute gradients of these losses - maybe generate plots of squared-loss v.s. Regularized loss

6. Lastly, students explore different variations of gradient descent
- https://ruder.io/optimizing-gradient-descent/
- Show some specific cases where accelerated GD/GD with momentum does much better
- AdamOptimizer

###II. How to Navigate Quiz Questions/Coding Assignment:
- Quiz questions and the coding assignment have been implemented in Google Colab.
- Simply navigate to the links for the google colab included in this repository.
- This repository also contains the full solutions which are also in colab.
