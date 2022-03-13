# ML_Naive_Bayes_Classifier

It is a multiclass classification problem. The data is used <a href="https://github.com/Krishnkumar542/ML_Naive_Bayes_Classifier/blob/main/iris_flower_dataset.csv">irish flower dataset</a>. In this dataset the number of observations for each class is balanced. There are 210 observations with 4 input variables and 1 output variable. The variable names are as follows:

- Sepal length in cm
- Sepal width in cm
- Petal length in cm
- Petal width in cm
- Species

Let’s use this standard iris dataset to predict the Species of the flower using 4 different features: sepal length, sepal width, petal length, and petal width. This data is work well with the Gaussian Naive Bayes classifier with an accuracy of 95%.

Initially, we divided the datasets into training (keeping 70% data for training purposes) and test data (the rest 30% data for testing purposes). After that most important thing is to check which type of classification model work well this dataset. There are three types of Naive Bayes Classifications:
1. Gaussian Naive Bayes
2. Multinomial Naive Bayes
3. Bernoulli Naive Bayes

We train the model with the above classification methods and then verify the accuracy score with the help of test data. The bar chart of the model accuracy is shown below;

### Model Accuracy:

![Model Accuracy](https://github.com/Krishnkumar542/ML_Naive_Bayes_Classifier/blob/main/Accuracy.png)

After running the model, the accuracy score obtained for the different types of the Naive Bayes Classifications model are;
1. Gaussian Naive Bayes >> 95%
2. Multinomial Naive Bayes >> 93%
3. Bernoulli Naive Bayes >> 25%

### Accuracy Report:

![Accuracy Report](https://github.com/Krishnkumar542/ML_Naive_Bayes_Classifier/blob/main/Accuracy_report.png)

From the above bar chart, it is clear that the most accurate model is Gaussian Naive Bayes which work well with an accuracy of 95%. Now, working with this classification type, the precision, recall and f1- score is estimated as shown in the above report. It indicates the model accurately predict the setosa flower whereas the versicolor and virginica flowers gives a slight error during the prediction.

### Confusion Matrix:

![Confusion Matrix](https://github.com/Krishnkumar542/ML_Naive_Bayes_Classifier/blob/main/CM.png)

The above confusion matrix predicts well-given flowers based on their different features such as sepal length, sepal width, petal length, and petal width. The model accurately predict setosa flower 16 times after training the data. Similarly, the versicolor and virginica flowers model accurately predict 22 time. However, only two times model predict versicolor flower as virginica flower and one time predict virginica flower as versicolor flower. Hence, it work well as shown in the report.

## Summary
Now, let's summarize the classification model and its accuracy. From the above confusion matrix, it is noticeable that only two times model predict versicolor flower as virginica flower and one time predict virginica flower as versicolor flower. Otherwise, classifier works well and predict flower same as actual flower depending upon different features such as sepal length, sepal width, petal length, and petal width. The accuracy score of the Gaussian Naive Bayes model is obtained 95%. Also, the precision, recall and f1- score are estimated as shown in the above report.
