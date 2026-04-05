ex-12
Nikunj Deep Upadhyay
Entc b1

THEORY
1. Introduction to Pandas

Pandas is a Python library used for data analysis and manipulation. It provides two main data structures:

Series → 1D data
DataFrame → 2D tabular data (rows & columns)

It is widely used for:

Data cleaning
Data transformation
Statistical analysis
Handling structured datasets
2. Reading Data

Data can be loaded from files such as CSV using:

pd.read_csv()

This converts external data into a DataFrame for processing.

3. Data Exploration

Basic operations to understand data:

head() → First few rows
info() → Data types & structure
value_counts() → Frequency of values
4. Frequency Analysis

Used to count occurrences:

value_counts() → Counts frequency of each category
value_counts(normalize=True) → Gives percentage distribution

Example:

Grade distribution
Category-wise orders
5. Data Filtering

Used to extract specific data:

Boolean conditions

Example:

df[df['Category'] == 'Electronics']
6. Sorting Data

Arrange data in ascending/descending order:

sort_values(by='column_name')
7. Grouping Data

Grouping allows aggregation:

groupby()

Example:

Department-wise grade distribution
8. Cross Tabulation

Used to analyze relationship between two variables:

pd.crosstab()

Example:

Department vs Gender
Category vs Payment Method
9. Unique Values
unique() → List unique elements
nunique() → Count of unique elements
10. Data Analysis Concepts Used

From your notebook:

Student performance analysis
Gender distribution
Department-wise comparison
E-commerce order analysis
Customer behavior analysis

ALGORITHM
Algorithm 1: Student Data Analysis
Start
Import pandas library
Load dataset using read_csv()
Display dataset
Count students in each grade using value_counts()
Count gender distribution
Calculate percentage of grades
Count students in each department
Perform cross tabulation (Department vs Gender)
Perform normalized cross tab (Department vs Grade %)
Group data using groupby() for detailed analysis
Display results
End
Algorithm 2: E-Commerce Order Analysis
Start
Import pandas
Create dataset using dictionary
Convert dictionary to DataFrame
Display dataset
Count frequency of categories
Count payment method usage
Calculate percentage distribution
Filter data for specific category (e.g., Electronics)
Sort data based on category
Find unique categories using unique()
Count number of unique categories using nunique()
Perform cross tabulation (Category vs Payment Method)
Display results
End

Conclusion

This notebook demonstrates:

Data handling using Pandas
Statistical analysis of categorical data
Real-world applications
