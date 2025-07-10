# Logistic_Regression
1.Logistic Regression is a supervised learning algorithm primarily used for binary classification.
2.Logistic Regression is used for binary classification — answering questions like:
  2.1. Is this spam or not spam?
  2.2. Is this tumor malignant or benign?
  2.3. Will the customer buy or not?

3. Its output function Y_hat = 1/(1+exp(-1*(wx+b))) 
4. here w is the weight and b is the bias and more importantly x is the **feature array** and the output Y_hat is also an **array** with values ranging between 0 and 1.
5. The loss function for Logistic Regression is given by:
   Loss = -(y*log(y_hat) + (1-y)*log(1-Y_hat))
6. Gradient decent would give us the most suitable weights and bias value by searching for that combination of weights and bias value where the cost function reaches the minimum value, cost function value              determines the difference between the predicted and the output values.
7. minimising this cost function results in good prediction.
