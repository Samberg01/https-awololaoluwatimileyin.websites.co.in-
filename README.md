# https-awololaoluwatimileyin.websites.co.in-
data analysis 
import pandas as pd

# Load the dataset
data = pd.read_csv('your_dataset.csv')

# Display the first 5 rows of the dataset
print(data.head())

# Get a summary of statistics
print(data.describe())

# Check for missing values
print(data.isnull().sum())

# Perform data cleaning, if necessary
# data = data.dropna()  # Example: Remove rows with missing values

# Perform a simple analysis, such as finding the mean of a column
mean_value = data['your_column_name'].mean()
print(f"The mean of your_column_name is: {mean_value}")

# Visualize data with a plot (requires matplotlib)
import matplotlib.pyplot as plt

data['your_column_name'].hist()
plt.show()
