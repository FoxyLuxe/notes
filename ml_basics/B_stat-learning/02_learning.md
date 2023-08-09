# Statistical Learning

In a general form, the statistical learning is a method to map input variables with output variables through a mathematical model that can simulate a real one. 

$X$: Vector of predictors such $(X_1,X_2,...,X_p)$ is a collection of $p$ predictors.
$Y$: Vector of the quantitive response such $(Y_1,Y_2,...,Y_k)$ is a collection of $k$ outputs.
$\epsilon$: The irreducible error of the map function.

$$Y = f(X)+\epsilon$$

## Square error

It can be taken two error from the map function, the explicit error on general expression $\epsilon$ refers to the irreducible error and the not fitted version of $\hat{f}$ contains the reducible error.

$$E(Y-\hat{Y})^2 = [f(X)-\hat{f}(X)]^2+Var(\epsilon)$$

## Prediction vs Inference

### Prediction

A prediction is an estimation of an output $Y$ for a given input $X$.

$$ \hat{Y} = \hat{X} $$

