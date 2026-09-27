# Iris Flower Classification

## OASIS INFOBYTE — Data Science Internship

### Task 1: Iris Flower Classification

## Objective

The objective of this project is to build machine learning classification models that identify Iris flower species based on their physical measurements.

The three species are:

- Setosa
- Versicolor
- Virginica

## Dataset

The Iris dataset was loaded using `sklearn.datasets.load_iris()`.

The dataset contains 150 observations and four numerical features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Exploratory Data Analysis

The project includes:

- Dataset shape and data type inspection
- Missing-value checking
- Descriptive statistics
- Pairplot visualization
- Box plots for the four features
- Feature selection discussion

The visual analysis indicated that petal length and petal width provide clearer separation between the Iris species.

## Machine Learning Models

Two classification models were trained:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)

The dataset was divided into:

- 80% training data
- 20% testing data

## Model Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 96.67% |
| K-Nearest Neighbors (KNN) | 100.00% |

Based on this test split, KNN achieved the higher accuracy.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Files

- `Iris_Flower_Classification.ipynb` — Complete analysis and machine learning implementation
- `README.md` — Project documentation

## Conclusion

The Iris dataset was successfully analyzed and classification models were developed to predict the Iris species. Both models performed well on the test dataset, with KNN achieving 100% accuracy on the selected test split.