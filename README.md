# Neural-Network-NN
In this exercise you'll try to build a neural network that predicts the price of a house according to a simple formula.
So, imagine if house pricing was as easy as a house costs 50k + 50k per bedroom, so that a 1 bedroom house costs 100k, a 2 bedroom house costs 150k etc.
How would you create a neural network that learns this relationship so that it would predict a 7 bedroom house as costing close to 400k etc.
Hint: Your network might work better if you scale the house price down. You don't have to give the answer 400...it might be better to create something that predicts the number 4, and then your answer is in the 'hundreds of thousands' etc.



Optimizers: Optimizer are the algorithm or methods used to change the attributes of your neural network such as weights and learning rate.
SGD (Stochastic Gradient Descent):
SGD performs frequent updates with a high variance, causing the objective function to fluctuate heavily. SGD’s fluctuation enables it to jump from a local minima to a potentially better local minima.
Neural networks are trained using stochastic gradient descent and require that you choose a loss function when designing and configuring your model.
There are many loss functions to choose from and it can be challenging to know what to choose, or even what a loss function is and the role it plays when training a neural network.
Mean Squared Error loss, or MSE for short, is calculated as the average of the squared differences between the predicted and actual values. The result is always positive regardless of the sign of the predicted and actual values and a perfect value is 0.0. The loss value is minimized, although it can be used in a maximization optimization process by making the score negative.

