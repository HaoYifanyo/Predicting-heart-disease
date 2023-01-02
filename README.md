# Predicting-heart-disease
The project for course 'CS-C3240 - Machine Learning D' at Aalto University.

|  | Random Forest | K-means |
| --------------- | --------------- | --------------- |
| Training Accuracy | 0.86 | 0.83 |
| Validation Accuracy | 0.83 | 0.79 |

In this project, I used one supervised method and one unsupervised method to predict heart
disease. Both the training and validation accuracy of the supervised method is higher than unsupervised, which might indicate that the labels provide helpful information.

For random forest, the validation and test errors are greater than the training errors, though
the difference is minor. It does not seem to be the optimal result. The reasons may include
possible overfitting and not having a large enough data set. To improve the model, I will adjust
the parameters of the random forest to find a better test accuracy, and a larger dataset is needed.

For k-means, I think the result is quite good, despite the inevitable differences between it and
supervised methods. To improve it, I will combine PCA/kernel PCA with k-means. If the dimensions can be reduced without a large decrease in accuracy, they can be used to deal with
data more quickly and efficiently.
