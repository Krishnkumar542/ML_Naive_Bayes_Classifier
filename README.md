# ML_Naive_Bayes_Classifier

It is a multiclass classification problem. The data is used <a href="https://github.com/Krishnkumar542/ML_Naive_Bayes_Classifier/blob/main/iris_flower_dataset.csv">irish flower dataset</a>. In this dataset the number of observations for each class is balanced. There are 210 observations with 4 input variables and 1 output variable. The variable names are as follows:

- Sepal length in cm
- Sepal width in cm
- Petal length in cm
- Petal width in cm
- Species

Let’s use this standard iris dataset to predict the Species of flower using 4 different features: Sepal Length, Sepal Width, Petal Length, and Petal Width. This data is work well with the Gaussian Naive Bayes classifier with the accuracy of 95%.

Initially, we divided the datasets into training (keeeping 70% data for training purpose) and test data (rest 30% data for testing purpose). After that most important thing is to check which type of clssification model work well this dataset. There are three types of Naive Bayes Classifications:
1. Gaussian Naive Bayes
2. Multinomial Naive Bayes
3. Bernoulli Naive Bayes

We train the model with this above classification method and then verify the accuracy score with the help of test data. The bar chart of the model accuracy is shown below;

### Model Accuracy:

![Model Accuracy](https://github.com/Krishnkumar542/ML_Naive_Bayes_Classifier/blob/main/Accuracy.png)
After running the model, the accuracy score obtained for the different types of the Naive Bayes Classifications are;
1. Gaussian Naive Bayes >> 95%
2. Multinomial Naive Bayes >> 93%
3. Bernoulli Naive Bayes >> 25%

### Accuracy Report:

![Accuracy Report](https://github.com/Krishnkumar542/ML_Naive_Bayes_Classifier/blob/main/Accuracy_report.png)

### Confusion Matrix:

![Confusion Matrix](https://github.com/Krishnkumar542/ML_Naive_Bayes_Classifier/blob/main/CM.png)

## Summary
Now, let's talk summarize the classification and its accuracy. From the above confusion matrix, it is noticeable that only two times model predict versicolor flower as virginica flower and one time predict virginica flower as versicolor flower. Otherwise, classifier works well and predict flower same as actual flower depending upon different features such as Sepal Length, Sepal Width, Petal Length, and Petal Width. The accuracy score of the Gaussian Naive Bayes model is obtained 95%. Also, the precision, recall and f1- score are estimated as shown above report.
