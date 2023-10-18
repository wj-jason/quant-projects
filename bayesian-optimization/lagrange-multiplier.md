# Lagrange Multipliers

The Langrange multiplier is used to optimize some function $f$ subject to a constraint $g$.

## Definition

Simplifying to $\mathbb{R}^3$, we want the highest or lowest value of $f(x,y)$ while ensuring $g(x,y)$ is satisfied. 

In $\mathbb{R}^2$, we can vary the contour lines of $f$ until is it tangent to $g$. Since the gradient vector is always perpendicular to the contour lines, when the contour line of $f$ is tangent to $g$, the gradient of each are linearly dependent. More formally:

$$\nabla f(x^{\ast},y^{\ast})=\lambda \nabla g(x^{\ast},y^{\ast})$$

for extrema $(x^{\ast},y^{\ast})$ where $\lambda$ is the Lagrange multiplier.

## Motivation

Suppose the contours of $f$ given by $f(x,y)=d$ for various $d$, and the contours of $g$ similarly given by $g(x,y)=c$. We will walk along $g=c$, while observing the $\nabla f$ as we go. If $\nabla f$ has any component along the constraint, $f$ must have a higher or lower point along the constraint. Therefore, if we continue to walk along the constraint until reaching a point where $\nabla f$ is normal to the constraint, $f$ is instantaneoulsy not changing at that point and an extrema has been found. 
