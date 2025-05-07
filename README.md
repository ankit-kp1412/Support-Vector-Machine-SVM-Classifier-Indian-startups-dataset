# Support-Vector-Machine-SVM-Classifier-Indian-startups-dataset

🎯 **Objective:**

>The objective of this assignment is to implement Support Vector Machine (SVM) classification on the provided dataset. You will learn how to preprocess the data, train an SVM model, and evaluate its performance.

**Tasks to Perform:**

1. Data Exploration:
>Load the dataset and inspect the first few rows.

>Explore the dataset by checking for null values, understanding the features, and summarizing the data using basic statistics.

2. Data Preprocessing:
>Handle any missing values if they exist.

>Encode categorical variables using techniques such as One-Hot Encoding or Label Encoding, depending on the nature of the categorical data.

>Scale the numerical features using StandardScaler or MinMaxScaler to ensure all features contribute equally to the model.

>Split the dataset into training and testing sets using an 80-20 split ratio. The training set will be used to train the model, and the testing set will evaluate its performance.

3. SVM Implementation:
>Use the SVC class from Scikit-learn to train an SVM classifier on the training data.

>Experiment with different kernels (linear, poly, rbf, sigmoid) and discuss how each kernel affects the model's performance.

4. Model Prediction:
>Use the trained SVM model to predict the class labels of the testing set.

>Compare the predicted labels with the actual labels to assess the model's performance.

5. Model Evaluation:
>Confusion Matrix: Display the confusion matrix to understand the distribution of true positives, false positives, true negatives, and false negatives.

>Classification Report: Generate a classification report that includes precision, recall, f1-score, and support for each class.

>Accuracy: Calculate the overall accuracy of the model on the test set.

>visualize the decision boundary created by the SVM models.
