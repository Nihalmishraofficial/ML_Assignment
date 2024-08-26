# ML_Assignment
# Iris Dataset Exploration, Splitting and Linear Regression Implementation

## 1. Dataset Exploration

### Overview:
In this program, we perform an initial exploration of the famous Iris dataset, which contains 150 samples of iris flowers from three species: Iris setosa, Iris versicolor, and Iris virginica. The dataset includes four features: sepal length, sepal width, petal length, and petal width.

### Key Steps:
- **Loading the Dataset:** We start by loading the Iris dataset, which is available through popular libraries like scikit-learn.
- **Data Visualization:** We use various plotting techniques to visualize the relationships between different features and species.
- **Summary Statistics:** The program calculates summary statistics (mean, median, standard deviation, etc.) for each feature to understand the data distribution.

### Purpose:
This exploration helps in understanding the dataset, identifying any patterns, and preparing for further analysis and model implementation.

---

## 2. Data Splitting

### Overview:
This program involves splitting the Iris dataset into training and testing subsets to evaluate the performance of a predictive model. Proper data splitting is crucial to prevent overfitting and to ensure that the model generalizes well to unseen data.

### Key Steps:
- **Data Partitioning:** The dataset is split into training and testing sets, typically using an 80-20 split. This is achieved using functions like `train_test_split` from scikit-learn.
- **Training Set:** The training set is used to train the model.
- **Testing Set:** The testing set is used to evaluate the model's performance.

### Purpose:
Data splitting is a fundamental step in machine learning pipelines to ensure that the model's performance is evaluated on data that it hasn’t seen during training, providing an unbiased estimate of its accuracy.

---

## 3. Implementing Linear Regression

### Overview:
This program focuses on implementing linear regression on predictiing the salary of the user and mean squared error based on year of experience . Linear regression is a simple and commonly used algorithm that models the relationship between a dependent variable and one or more independent variables.

### Key Steps:
- **Model Selection:** We choose linear regression as our model, which assumes a linear relationship between the dependent and independent variables.
- **Training the Model:** The model is trained using the training data, where it learns the relationship between the input features and the target variable.
- **Model Evaluation:** After training, the model is tested on the testing set to evaluate its predictive performance. Metrics such as Mean Squared Error (MSE) or R-squared are used for evaluation.

### Purpose:
The purpose of this program is to implement and understand the workings of linear regression, a fundamental machine learning algorithm. By predicting salary based on experience ,we can gain insights into the linear relationships within the data.

---