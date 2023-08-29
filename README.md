## 2D Data Analysis with Linear Regression
This Python script analyzes a 2D dataset using linear regression techniques. It reads data from a CSV file containing information about Cambodia and Myanmar from 2001 to 2020, performs data preparation, linear regression, and evaluation using various metrics. The script also includes data visualization using Seaborn.

## Prerequisites
Before you begin, ensure you have the following libraries installed:

- pandas

- matplotlib

- seaborn

- numpy



You can install them using pip:
```bash
pip install pandas matplotlib seaborn numpy
```


## Getting Started
1.Clone the repository to your local machine:
```bash
git clone https://github.com/your-username/2d-data-analysis.git
```



2.Run the script in Jupyter



## Dataset Description
The dataset consists of the following columns:

## Categories:
1.Country

2.Year



## Target:
1.Percentage of Undernourishment Prevalence (3-Year Average)



## Features:
1.Binary Categorical

2.GDP per Capita (USD)

3.Annual Inflation Rate (%)

4.Gross per capita Production Index Number (2014-2016 = 100)



## Data Preparation
The script performs the following data preparation steps:

1.Reads the dataset from a remote CSV file.

2.Extracts the specified features and target columns.

3.Splits the data into training and test sets.

4.Normalizes the features using Z-score normalization.

5.Prepares the features and target data as NumPy arrays.



## Data Visualization
The script includes scatterplots using Seaborn to visualize the relationships between the features and the target variable. Scatterplots are created for each feature against the target variable, with separate plots for real and predicted values.



## Linear Regression and Metrics
The script applies linear regression to the dataset. It calculates the cost function, performs gradient descent to optimize the model parameters (beta), and predicts the target variable.

Metrics for model evaluation are computed, including:

- Mean Squared Error (MSE)

- Coefficient of Determination (R²)

- Adjusted Coefficient of Determination (Adjusted R²)

- Standard Error of Regression (Regression S)



## Customization
You can customize the script by modifying the following variables:

- features: Choose the features you want to use for analysis.

- targets: Specify the target variable for prediction.

- iterations and alpha: Adjust the number of gradient descent iterations and learning rate for optimization.



## Results
After running the script, you will see the calculated metrics for model evaluation. These metrics provide insights into the performance of the linear regression model on the given dataset.

