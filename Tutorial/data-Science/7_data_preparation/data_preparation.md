# Data Preparation
Before analyzing data, a Data scientist must extract the data, and make it clean and valueable.

## Extract and Read Data With Pandas
- Before data can be analyzed, it must be imported/extracted.
- We use the `read_csv()` function from pandas to import a CSV file with the health data.
- [Click here to see the code with explanation](data_prep.ipynb)

## Data Categories
To analyze data, we also need to know the types of data we are dealing with. Data can be split into three main categories:
- **Numerical:** Contains numerical values. Can be divided into two categories:
  - **Discrete:** Numbers are counted as "whole". Example: We can not have trained 2.5 sessions, it is either 2 or 3.
  - **Continuous:** Numbers can be of infinite precision. For example, We can sleep for 7 hours, 30 mintues and 20 seconds, or 7.533 hours.
- **Categorial:** Contains values that cannot be measured up against each other. Example: A color or a type of training.
- **Ordinal:** Contains categorical data that can be measured up against each other. Example: School grades where A is better than B and so on.

## Data Types
- [Click here to see the code with explanation](data_prep.ipynb)

## Analyze the Data
- [Click here to see the code with explanation](data_prep.ipynb)