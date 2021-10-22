# ANALYZE COMPANY XYZ’s SUPERMARKETS DATA ACROSS THE COUNTRY 

Company XYZ owns a supermarket chain across the country. Each major branch located in 3 cities across the country recorded sales information for 3 months. 
The aim of this project is to use the data recorded to help the company understand sales trends and determine its growth.

## PROJECT STEPS

### STEP 1 – Loading the Dataset
The dataset from each branch of the 3 branches is combined using the glob method into one dataset for easy analysis. 
### STEP 2 – Data Exploration
The necessary libraries are imported to explore the dataset.
Function like head, shape, info, describe, etc. are used to explore the dataset.
### STEP 3 – Dealing with Date Time Features
The data type of the Date and Time column is changed from Object data type to datetime data type using the pandas.to_datetime() feature, New columns are created from the date and time column namely day, month, year and hour and The unique method is used to find the number of unique hours in the Hour column.
### STEP 4 – Unique Values in Columns
Categorical Columns (Columns that have the Object data type) are gotten and their unique values are derived using the unique(), nunique() and value_counts() functions.
### STEP 5 – Aggregation with Groupby
•	A groupby object is created with the City Column, and aggregation function of sum and mean to obtain more information from the dataset.
### STEP 6 – Data Visualization
The dataset is graphically explored using charts generated with the Seaborn visualization library. 



# Insights

To-Do - Explain the insights you were able to uncover from the analysing the datasets.

# Future Work

To-Do - Suggest tasks you might include in future work to make this project more robust.

# Standout Section

To-Do - Explain what you did differently in the project following the instructions in the notebook.

# Executive Summary.

To-Do - Include your Executive Summary document in your repository.
