ML basics ,based on courses 
1. https://docs.microsoft.com/en-us/learn/paths/ml-crash-course/
others

Classification: 
 1. Naive Bayes classification : The bayesian theorem to calculate the probabilty of a data point belonging to a particular class.
        \[ P(A | B) = \frac {P(B | A) \times P(A)} { P(B)} \]
 2. Logistic Regression : A logistic function is applied to the outcome of linear regression.(sigmoid function)
            1 / (1 + e^-value)
 3. K-nearest classification model : K number of nearest points around the data point to be predeicted are taken into consideration. These K points at this time, already belong to a class.The data point under consideration, is said to belong to the class with which most number of points from these k points belong to.
 4. SVM classification : Support Vector Machines outputs an optimal line of separation between the classes based on the training data served as input. This line of separation is called a hyperplane in a multi dimensional environment
 5. Random forest classification : Decision tree algorithms are efficient in eliminating columns that don't add value in predicting the output and in some cases, we are even able to see how a prediction was derived by backtracking the tree.The model performance is however improvised by taking an average of several such decision trees derived from the subsets of the training data. This approach is called the Random Forest classification.


