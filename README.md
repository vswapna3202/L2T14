## L2T14 - Capstone Project Linear Regression Analysis

### Overview

This capstone project involves performing linear regression analysis on the Boston housing dataset (`boston.csv`). The goal is to build a predictive model for housing prices using independent variables such as the average number of rooms (`rm`) and the proportion of the population with a low status (`lstat`). The project includes data cleaning, exploratory data analysis (EDA), model building, and evaluation.

### Instructions

### Setup and Installation

1. **Clone the Repository**
   - Clone this repository to your local machine:
     ```
     git clone https://github.com/vswapna3202/L2T14.git
     ```

2. **Navigate to the Project's Folder**
   - Navigate to the folder containing the project:
     ```
     cd L2T14 or cd <your-task-folder>
     ```

3. **Install Dependencies**
   - Ensure you have Python installed on your system. You can download it from the [official Python website](https://www.python.org/).
   - Install Jupyter Notebook to run the provided notebook:
     ```
     pip install notebook
     ```
   - Install necessary libraries such as `pandas`, `numpy`, `matplotlib`, and `scikit-learn`:
     ```
     pip install pandas numpy matplotlib scikit-learn
     ```

### Project Workflow

1. **Reading and Preparing the Data**
   - Read the `boston.csv` file into the Jupyter notebook `Capstone Linear Regression.ipynb`.
   - Clean and prepare the dataset if necessary.

2. **Exploratory Data Analysis (EDA)**
   - Perform EDA to gain insights into the dataset.
   - Visualize the distributions of the dependent variable and independent variables.
   - Identify any patterns or trends in the data.

3. **Linear Regression Model**
   - Use the following independent variables: `rm` (average number of rooms) and `lstat` (proportion of the population with low status).
   - Split the dataset into the independent variables and the single dependent variable.
   - Generate plots to explore the relationships between the independent variables and the dependent variable.

4. **Model Building and Evaluation**
   - Split the data into training and test sets using a split ratio of 75:25.
   - Build a multiple linear regression model using the training set with all the independent variables.
   - Print out the intercept and coefficients of the trained model.
   - Generate predictions for the test set.
   - Evaluate the model's performance by computing the mean squared error (MSE) or root mean squared error (RMSE) on the test set.
   - Generate an error plot to visualize the differences between the predicted and actual values in the test set.
   - Print the coefficients and interpret them within the context of the median value prediction.

5. **Summary**
   - Summarize the findings from the analysis, including insights from the exploratory data analysis, model performance, and any notable observations within the notebook.

### Running the Notebook

- Start Jupyter Notebook:
```
jupyter notebook
```
- Open the Jupyter notebook `Capstone Linear Regression.ipynb`.

## Dataset
- `boston.csv`: Contains data on various attributes of houses in Boston, including features like average number of rooms (`rm`), proportion of population with low status (`lstat`), and median value of owner-occupied homes (`medv`). [Source](<boston.csv>)

