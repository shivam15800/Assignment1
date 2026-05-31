Assignment Summary

This assignment focused on performing basic data exploration and data cleaning operations using the Pandas library in Python.

The dataset was loaded from a CSV file into a Pandas DataFrame and explored using functions such as head(), shape, dtypes, columns, and info() to understand its structure, datatypes, and overall contents.

Missing values were identified using isnull().sum() and handled appropriately by filling numeric missing values with 0 and categorical missing values with meaningful placeholders such as "No review", "Unknown Seller", and "Not Available".

The dataset was checked for duplicate rows using duplicated().sum(). Basic filtering operations were also performed to display products with ratings greater than 4.

The final_price column originally contained string values with currency symbols and formatting characters. These values were cleaned using regular expressions and converted into numeric format using pd.to_numeric() for proper processing.

A derived column named total_amount was created using initial_price and ratings_count to demonstrate column transformation and basic arithmetic operations in Pandas.

Finally, the cleaned dataset was exported as a new CSV file named cleaned_combined_dataset.csv.
