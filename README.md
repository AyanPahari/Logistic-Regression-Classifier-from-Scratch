
# Logistic Regression Classifier from Scratch

We will Implement a logistic regression classifier, which is trained
using gradient descent and cross-entropy error as the error function.

We use the linear model fθ(x1, x2) = θ0 + θ1x1 + θ2x2 and the logistic regression function σ(fθ(x1, x2)) =
1/(1+exp^−fθ(x1,x2)). Consider the initial weights as θ0 = −1, θ1 = 1.5, θ2 = 0.5, and learning rate as 0.1 (for gradient descent).

We will try to answer the following questions:

    i. What is the logistic model P(ˆy = 1|x1, x2) and its cross-entropy error
    function?

    ii. Use gradient descent to update θ0, θ1, θ2 for one iteration. Write down
    the updated logistic regression model.
    
    iii. At convergence of gradient descent, use the model to make predictions
    for all the samples in the test dataset. Calculate and report the accuracy, precision
    and recall to evaluate this model.
## Lending Club Dataset

Train Dataset

| Index 	| x1    	| x2    	| y 	|
|-------	|-------	|-------	|---	|
| 1     	| 0.346 	| 0.780 	| 0 	|
| 2     	| 0.303 	| 0.439 	| 0 	|
| 3     	| 0.358 	| 0.729 	| 0 	|
| 4     	| 0.602 	| 0.863 	| 1 	|
| 5     	| 0.790 	| 0.753 	| 1 	|
| 6     	| 0.611 	| 0.965 	| 1 	|


Test Dataset

| Index 	| x1    	| x2    	| y 	|
|-------	|-------	|-------	|---	|
| 1     	| 0.959 	| 0.382 	| 0 	|
| 2     	| 0.750 	| 0.306 	| 0 	|
| 3     	| 0.395 	| 0.760 	| 0 	|
| 4     	| 0.823 	| 0.764 	| 1 	|
| 5     	| 0.761 	| 0.874 	| 1 	|
| 6     	| 0.844 	| 0.435 	| 1 	|

Feel free to use your own dataset to test out the classifier

## Authors

- [@AyanPahari](https://github.com/AyanPahari)

