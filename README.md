# ML_Undersampling-and-Oversampling

I chose VSA drug as target varaible where I applied the Logistic Regression feature selection technique to select the best 9 features out of 12 by dropping the ID column. 
To oversampled data, I used SMOTE oversampling technique which focuses on the feature space to generate new instances with the help of interpolation between the positive instances that lie together. 
To undersampled data, I used the Random undersampling technique which involves randomly selecting examples from the majority class and deleting them from the training dataset. 
Then applied the min-max scaling approach to scale the values to a standard range. Then applied K-fold cross-validation technique where the number of folds is 10 on the dataset to evaluate the performance of the given machine learning algorithms. 
Average accuracy was taken from each classifier and later Friedman's test was applied to check if there is a significant difference between the models.
