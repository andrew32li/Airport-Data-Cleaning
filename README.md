# Airport-Data-Cleaning

Airline data often arrives in various formats, riddled with inconsistencies and irregularities. The airport_data function is designed to tackle this issue, providing a streamlined solution to clean and standardize airport data. The airport_data function takes a string of airline data and applies a series of transformations to ensure consistency and cleanliness. Here's how it works:

**Data Parsing**: The function first separates the data into rows and further splits them using semicolons to create a structured DataFrame.

**Type Conversion**: The 'FlightCodes' column is converted to integer type, ensuring numerical consistency.

**Missing Data Handling**: Missing 'FlightCodes' values are dynamically filled in by incrementing by 10 for each subsequent row.

**To-From Standardization**: The 'To_From' column is converted to capital case for uniformity. Additionally, it's split using underscores ('_') to create a more detailed breakdown of the information.

**Data Concatenation**: Repetitive data is combined with the original DataFrames for comprehensive insights.

**Airline Code Cleaning**: Columns are thoroughly cleaned, removing any non-alphabetic characters for consistency.
