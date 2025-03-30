🧠 Model Description
Lasso Regression (Least Absolute Shrinkage and Selection Operator) is a linear regression technique that includes an L1 penalty on the coefficients to enforce sparsity.

Mathematical Formulation
The Lasso Regression objective function is given by:

𝐽
(
𝜃
)
=
1
2
𝑚
∑
(
𝑦
𝑖
−
𝑦
𝑖
^
)
2
+
𝜆
∑
∣
𝜃
𝑗
∣
J(θ)= 
2m
1
​
 ∑(y 
i
​
 − 
y 
i
​
 
^
​
 ) 
2
 +λ∑∣θ 
j
​
 ∣
Where:

𝑚
m = Number of training examples

𝑦
𝑖
y 
i
​
  = Actual value

𝑦
𝑖
^
y 
i
​
 
^
​
  = Predicted value

𝜆
λ = Regularization parameter (controls the strength of the penalty)

𝜃
𝑗
θ 
j
​
  = Model parameters

Optimization
The optimization is done using Coordinate Descent, which iterates over each feature to minimize the objective function.

📊 Visualizations
Coefficient Shrinkage: Visualizes how increasing 
𝜆
λ shrinks coefficients.

Loss Curve: Tracks model convergence during training.

✨ Results
Demonstrated coefficient shrinkage as 
𝜆
λ increases.

Achieved good generalization performance by reducing overfitting.

Compared results with standard Linear Regression to show the effect of L1 regularization.
