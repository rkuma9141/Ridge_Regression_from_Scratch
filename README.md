# Ridge Regression

## Introduction
Ridge Regression ek regularized linear regression technique hai jo overfitting ko reduce karti hai.
Isme L2 regularization use hota hai.

## Model
y = m x + v

## Cost Function
J(m, v) = Σ (y_i − (m x_i + v))² + λ m²

Where:
m = slope  
v = intercept  
λ = regularization parameter  

## Formula (Single Variable)

m = Σ(x_i y_i) / (Σ(x_i²) + λ)

v = ȳ − m x̄

## Input Format

X values:
[ ]

Y values:
[ ]

Lambda (λ):
[ ]

## Steps
1. x̄ aur ȳ calculate karo  
2. Σ(xy) aur Σ(x²) nikaalo  
3. Formula se m nikaalo  
4. v = ȳ − m x̄

## Output
m (slope
