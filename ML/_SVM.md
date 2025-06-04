Linear model for supervised learning   
SVM tries to find a decision boundary (or hyperplane) 
that best separates data points of different classes 

Terminologies -   
1. Hyperplane:  
A decision boundary separating different classes 
2. Support Vectors:  
The closest data points to the hyperplane 
3. Margin:  
The distance between the hyperplane and the 
support vectors. 
4. Kernel:  
A function that maps data to a higher-dimensional 
space, enabling SVM to handle non-linearly 
separable data.(as was not possible in 2d)
5. Hard Margin:  
A maximum-margin hyperplane that perfectly 
separates the data 
6. Soft Margin:  
Allows some misclassifications by introducing 
slack variables, balancing margin maximization and 
misclassification penalties. 
7. Hinge Loss:  
A loss function penalizing misclassified points or 
margin violations, combined with regularization in 
SVM. 
8. Dual Problem:  
Involves solving for Lagrange multipliers associated 
with support vectors, facilitating the kernel trick 
and efficient computation. 