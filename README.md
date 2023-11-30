# Python_Repository 
# Data Analysis Helper Functions #

# Overview
This repository contains a collection of Python functions designed to simplify and enhance data analysis tasks. Created to support common data handling challenges, these functions are tailored for efficiency and ease of use in various data analysis scenarios.

# Purpose
The primary goal of this collection is to provide reusable code snippets that address frequent data manipulation and analysis needs. These functions are crafted to aid in quick and effective data processing, enabling users to focus more on analysis and less on the intricacies of data handling.

# FUNCTIONS
# call_archive(file_name, file_location)

* Purpose: Loads data from various file formats.

* Description: Given a file name and location, this function detects the file type (CSV or SQL) and loads the data accordingly.

# check_col(dataframe_name)

* Purpose: Checks for missing values in columns.

* Description: Iterates through each column of a DataFrame, comparing the count of non-null values against the total number of rows to identify missing data.

# list_null(dataframe_name)

* Purpose: Lists rows with null values.

* Description: Creates a DataFrame listing all rows from the input DataFrame that contain any null values, aiding in identifying missing data.
        
# convert_column_to_int(dataframe_name, column_name)

* Purpose: Converts a column to integer type.

* Description: Checks if a specified column exists in the DataFrame and converts its data type from float to integer.
        
# replace_value(dataframe_name, column_name, old_value, new_value)

* Purpose: Replaces specific values within a DataFrame column.

* Description: Substitutes a given value in a specified column with a new value, useful for data normalization or corrections.
        
# analyze_duplicates_and_uniques_as_table(dataframe_name)

* Purpose: Analyzes unique and duplicated values in each column.

* Description: Generates a summary table displaying the count of unique and duplicated values for each column in a DataFrame, useful for data quality assessment.


# Usage

Each function is documented with comments explaining its purpose and usage. Example usage is provided in the script for guidance.

# Contribution

Contributions to this collection are welcome! If you have suggestions or additional functions that can be included, feel free to create a pull request.


