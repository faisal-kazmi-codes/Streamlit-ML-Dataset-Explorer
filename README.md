# ML-Model-Datasets-Using-Streamlits 
This repository contains my machine learning models implementation code using streamlit in the Python programming language.<br><br>


## About Project : HyperTuneML Platform

<p>Complete Description about the project and resources used.</p>

- **Streamlit Website for Machine Learning Algorithms**: Developed a dynamic web application using Streamlit where users can interactively apply multiple supervised learning algorithms to various datasets. The app is designed to showcase **improved model accuracy** through **hyperparameter tuning** on diverse **real-world datasets**.
  
- **Data Visualization**: Implemented comprehensive data visualization features to illustrate the performance and results of the applied algorithms on different datasets. Visualizations include graphs, charts, and metrics to enhance understanding.
  
- **Hyperparameter Tuning for Enhanced Model Accuracy**: Users can select specific hyperparameters and datasets, with the app displaying the corresponding accuracy metrics. Interactive graphs visually depict the algorithm's performance, providing **practical insights** into predictive analytics.
  
- **Deployment**: Successfully deployed the web application using Streamlit, making it accessible online for users to utilize and explore.

## Algorithm Used :

<h2>Supervised Learning</h2>
--> Basically supervised learning is when we teach or train the machine using data that is well-labelled. <br><br>
--> Which means some data is already tagged with the correct answer.<br><br>
--> After that, the machine is provided with a new set of examples(data) so that the supervised learning algorithm analyses the training data(set of training examples) and produces a correct outcome from labeled data.<br><br>

<h3>i) K-Nearest Neighbors (KNN) </h3>
<br>
--> K-Nearest Neighbours is one of the most basic yet essential classification algorithms in Machine Learning.<br><br>
--> It belongs to the supervised learning domain and finds intense application in pattern recognition, data mining, and intrusion detection..<br><br>
--> In this algorithm,we identify category based on neighbors.<br><br>

<h3>ii) Support Vector Machines (SVM) </h3>
<br>
--> The main idea behind SVMs is to find a hyperplane that maximally separates the different classes in the training data. <br><br>
--> This is done by finding the hyperplane that has the largest margin, which is defined as the distance between the hyperplane and the closest data points from each class. <br><br>
--> Once the hyperplane is determined, new data can be classified by determining on which side of the hyperplane it falls. <br><br>
--> SVMs are particularly useful when the data has many features, and/or when there is a clear margin of separation in the data.<br><br>

<h3>iii) Naive Bayes Classifiers</h3>
<br>
--> Naive Bayes classifiers are a collection of classification algorithms based on Bayes’ Theorem. <br><br>
--> It is not a single algorithm but a family of algorithms where all of them share a common principle, i.e. every pair of features being classified is independent of each other.<br><br>
--> The fundamental Naive Bayes assumption is that each feature makes an independent and equal contribution to the outcome.<br><br>

<h3>iv) Decision Tree</h3>
<br>
--> It builds a flowchart-like tree structure where each internal node denotes a test on an attribute, each branch represents an outcome of the test, and each leaf node (terminal node) holds a class label.<br><br>
--> It is constructed by recursively splitting the training data into subsets based on the values of the attributes until a stopping criterion is met, such as the maximum depth of the tree or the minimum number of samples required to split a node.<br><br>
--> The goal is to find the attribute that maximizes the information gain or the reduction in impurity after the split.<br><br>

<h3>v) Random Forest</h3>
<br>
--> It is based on the concept of ensemble learning, which is a process of combining multiple classifiers to solve a complex problem and to improve the performance of the model.<br><br>
--> Instead of relying on one decision tree, the random forest takes the prediction from each tree and based on the majority votes of predictions, and it predicts the final output.<br><br>
--> The greater number of trees in the forest leads to higher accuracy and prevents the problem of overfitting.<br><br>

<h3>vi) Linear Regression</h3>
<br>
--> Regression: It predicts the continuous output variables based on the independent input variable. like the prediction of house prices based on different parameters like house age, distance from the main road, location, area, etc.<br><br>
--> It computes the linear relationship between a dependent variable and one or more independent features. <br><br>
--> The goal of the algorithm is to find the best linear equation that can predict the value of the dependent variable based on the independent variables.<br>
<br>

<h3>vii) Logistic Regression</h3>
<br>
--> Logistic regression is a supervised machine learning algorithm mainly used for classification tasks where the goal is to predict the probability that an instance of belonging to a given class or not. <br><br>
--> It is a kind of statistical algorithm, which analyze the relationship between a set of independent variables and the dependent binary variables. <br><br>
--> It is a powerful tool for decision-making.<br><br>
--> For example email spam or not. <br>

---
## Dataset Used :

<h2>Iris Dataset</h2>
--> Iris Dataset is a part of sklearn library.<br><br>
--> Sklearn comes loaded with datasets to practice machine learning techniques and iris is one of them. <br><br>
--> Iris has 4 numerical features and a tri class target variable.<br><br>
--> This dataset can be used for classification as well as clustering.<br><br>
--> In this dataset, there are 4 features sepal length, sepal width, petal length and petal width and the target variable has 3 classes namely ‘setosa’, ‘versicolor’, and ‘virginica’.<br><br>
--> Objective for a multiclass classifier is to predict the target class given the values for the four features.<br><br.
--> Dataset is already cleaned,no preprocessing required.<br>

<h2>Breast Cancer Dataset</h2>
--> The breast cancer dataset is a classification dataset that contains 569 samples of malignant and benign tumor cells. <br><br>
--> The samples are described by 30 features such as mean radius, texture, perimeter, area, smoothness, etc. <br><br>
--> The target variable has 2 classes namely ‘benign’ and ‘malignant’.<br><br>
--> Objective for a multiclass classifier is to predict the target class given the values for the features.<br><br>
--> Dataset is already cleaned,no preprocessing required.<br>

<h2>Wine Dataset</h2>
--> The wine dataset is a classic and very easy multi-class classification dataset that is available in the sklearn library.<br><br>
--> It contains 178 samples of wine with 13 features and 3 classes.<br><br>
--> The goal is to predict the class of wine based on the features.<br><br>
--> Dataset is already cleaned,no preprocessing required.<br>

<h2>Digits Dataset</h2>
--> The digits dataset is a classic multi-class classification dataset that is available in the sklearn library.<br><br>
--> It contains 1797 samples of digits with 10 classes.<br><br>
--> The goal is to predict the class of digit based on the features.<br><br>
--> Dataset is already cleaned,no preprocessing required.<br>

<h2>Diabetes Dataset</h2>
--> The diabetes dataset is a regression dataset that is available in the sklearn library.<br><br>
--> It contains 442 samples and 10 classes.<br><br>
--> Dataset is already cleaned,no preprocessing required.<br>

<h2>Naive bayes classification data</h2>
--> Dataset is taken from: <a href="https://www.kaggle.com/datasets/himanshunakrani/naive-bayes-classification-data"><img src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/189_Kaggle_logo_logos-1024.png" height =40 width=40 title="Naive bayes classification data"> </a><br><br>
--> Contains diabetes data for classification.<br><br>
--> The dataset has 3 columns-glucose, blood pressure and diabetes and 995 entries.<br><br>
--> Column glucose and blood pressure data is to classify whether the patient has diabetes or not.<br><br>
--> Dataset is already cleaned,no preprocessing required.<br>

<h2>Cars Evaluation Dataset</h2>
--> Dataset is taken from: <a href="https://www.kaggle.com/datasets/elikplim/car-evaluation-data-set"><img src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/189_Kaggle_logo_logos-1024.png" height =40 width=40 title="Cars Evaluation Dataset" alt="Cars Evaluation Dataset"> </a><br><br>
--> Contains information about cars with respect to features like Attribute Values:<br><br>
<table>
<td>1. buying v-high, high, med, low </td>
<td>2.maint v-high, high, med, low </td>
<td>3.doors 2, 3, 4, 5-more </td>
<td>4. persons 2, 4, more </td>
<td>5. lug_boot small, med, big</td>  
<td>6.safety low, med, high</td>  </table>
--> Target categories are:<br><br>
<table>
  <td>1. unacc 1210 (70.023 %)</td>
  <td>2. acc 384 (22.222 %)</td>
  <td>3. good 69 ( 3.993 %)</td>
  <td>4. v-good 65 ( 3.762 %)</td></table>
--> Contains Values in string format.<br><br>
--> Dataset is not cleaned, preprocessing is required.<br>

<h2>Salary Dataset</h2>
--> Dataset is taken from: <a href="https://www.kaggle.com/datasets/abhishek14398/salary-dataset-simple-linear-regression
"><img src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/189_Kaggle_logo_logos-1024.png" height =40 width=40 title="Salary Dataset" alt="Salary Dataset"> </a><br><br>
--> Contains Salary data for Regression.<br><br>
--> The dataset has 2 columns-Years of Experience and Salary and 30 entries.<br><br>
--> Column Years of Experience is used to find regression for Salary.<br><br>
--> Dataset is already cleaned,no preprocessing required.<br>

<h2>Heart Disease Dataset</h2>
--> Dataset is taken from: <a href="https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset"><img src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/189_Kaggle_logo_logos-1024.png" height =40 width=40 title="Heart Disease Dataset" alt="Heart Disease Dataset"> </a><br><br>
--> Contains heart disease dataset for Classification.<br><br>
--> The Shape of dataset is 303 X 16.<br><br>
--> Dataset is not cleaned, preprocessing is required.<br>

<h2>Titanic Dataset</h2>
--> Dataset is taken from: <a href="https://www.kaggle.com/datasets/vinicius150987/titanic3/data"><img src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/189_Kaggle_logo_logos-1024.png" height =40 width=40 title="Titanic Dataset" alt="Titanic Dataset"> </a><br><br>
--> Contains Titanic dataset for classification tasks (predicting survival).<br><br>
--> The Shape of dataset is 1309 X 14.<br><br>
--> Dataset is not cleaned, preprocessing is required.
