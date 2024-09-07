# Binary Classification and Decision Boundary Visualization with Logistic Regression and SVM on the Iris Dataset

This program performs binary classification using Logistic Regression and Support Vector Machine (SVM) with the Iris dataset. First, the data points where species equals 2 (Virginica) are excluded from the dataset, and the two features sepal width (cm) and petal width (cm) are used to classify between 0 (Setosa) and 1 (Versicolor). The dataset is then split into training and testing sets, and both Logistic Regression and SVM models are trained. After training, predictions are made on the test data, and the model's performance is evaluated using metrics such as accuracy, recall, precision, and the confusion matrix. Additionally, arbitrary data points are added to verify their classification results. Finally, the decision boundaries of each model are visualized on a graph to visually inspect the classification results and their boundaries.