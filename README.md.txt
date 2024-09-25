Iris Flower Classification Project

Overview

This project aims to classify iris flowers into three species—Setosa, Versicolor and Virginica—using machine learning techniques. The classification is based on measurements of the iris flowers' physical attributes, specifically sepal length, sepal width, petal length and petal width.

Dataset

The dataset used in this project is `IRIS.csv`, which contains the following columns:

- sepal_length: Length of the sepal (cm)
- sepal_width: Width of the sepal (cm)
- petal_length: Length of the petal (cm)
- petal_width: Width of the petal (cm)
- species: The species of the iris flower (Setosa, Versicolor, Virginica)

Libraries Used

- Pandas: For data manipulation and analysis
- NumPy: For numerical computations
- Matplotlib: For basic data visualization
- Seaborn: For advanced data visualization
- Plotly: For interactive visualizations
- Scikit-Learn: For building and evaluating the classification model

Steps Involved

1. Load Data: Read the dataset into a Data frame
2. Exploratory Data Analysis (EDA): Understand the data structure and visualize relationships using pair plots and box plots
3. Data Cleaning: Check for missing values and handle them if necessary
4. Feature Selection: Identify which features are most relevant for classification
5. Split Data: Divide the dataset into features and target variables, and then into training and testing sets
6. Model Building: Use K-Nearest Neighbors (KNN) to build the classification model
7. Evaluation: Assess the model's performance using accuracy, confusion matrix and classification report

Results

The model effectively classifies iris flowers with high accuracy, allowing for predictive insights into flower species based on their measurements.

How to Run
1. Clone the repository.
2. Ensure you have the required libraries installed (pip install pandas numpy matplotlib seaborn plotly scikit-learn).
3. Run the Jupyter Notebook to see the results.
