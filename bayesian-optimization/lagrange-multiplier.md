# Lagrange Multipliers

The Langrange multiplier is used to optimize some function $f$ subject to a constraint $g$.

### Theory

We want to maximize the function $f(x,y)$ on the set $g(x,y)$.

We can vary the contour lines of $f$ until is it tangent to $g$. Since the gradient vector is always perpendicular to the contour lines, when the contour line of $f$ is tangent to $g$, the gradient of each are linearly dependent. More formally:

$$\nabla f(x^{\ast},y^{\ast})=\lambda \nabla g(x^{\ast},y^{\ast})$$

where $\lambda$ is the Lagrange multiplier.

### Example

Suppose $f(x,y)=x^2y$ on the set $x^2+y^2=1$.
