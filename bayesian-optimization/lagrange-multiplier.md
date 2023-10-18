# Lagrange Multipliers

The Langrange multiplier is used to optimize some function $f$ subject to a constraint $g$.

### Theory

Simplifying to $\mathbb{R}^3$, we want the highest or lowest value of $f(x,y)$ while ensuring $g(x,y)$ is satisfied. 

We can vary the contour lines of $f$ until is it tangent to $g$. Since the gradient vector is always perpendicular to the contour lines, when the contour line of $f$ is tangent to $g$, the gradient of each are linearly dependent. More formally:

$$\nabla f(x^{\ast},y^{\ast})=\lambda \nabla g(x^{\ast},y^{\ast})$$

where $\lambda$ is the Lagrange multiplier.
