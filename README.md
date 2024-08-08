# Cryptocurrency-data-analysis
Data exploration and preprocessing on a cryptocurrency dataset stored

# Part 1: Importing Libraries
numpy: Useful for numerical operations and linear algebra.

pandas: Essential for data manipulation and analysis.

matplotlib.pyplot: A plotting library for creating static, animated, and interactive visualizations.

seaborn: Built on top of matplotlib, it provides a high-level interface for drawing attractive and informative statistical graphics.

LabelEncoder: Converts categorical labels into numeric form.

KMeans: An algorithm for clustering data.
# Part 2: Loading the Dataset
The 'cryptocurrency.csv' file is loaded into a Pandas DataFrame ('df'), which allows for easy data manipulation and analysis.
# Part 3: Exploring the Dataset
'df.shape': Returns the dimensions of the dataset (number of rows and columns).

'df.info()': Provides a concise summary of the DataFrame, including the data types of each column and the number of non-null values.

'df.isnull().sum()': Shows the count of missing values in each column.

'df.describe()': Generates descriptive statistics that summarize the central tendency, dispersion, and shape of the dataset’s distribution.
# Part 4:Analyzing Unique Values
Check for unique values in various columns, which helps in understanding the diversity or repetition in categorical data.
# Part 5: Dropping Unnecessary Columns
Unnecessary columns are removed from the DataFrame to simplify the dataset for further analysis. The axis=1 parameter indicates that columns, not rows, are being dropped.
# Part 6: Label Encoding
LabelEncoder is used to convert the 'name' column into numerical values, as many machine learning algorithms require numerical input.
