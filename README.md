# Description:
This Jupyter Notebook contains a comprehensive data cleaning and preprocessing workflow for an Amazon product dataset. The dataset includes various product details such as product ID, name, category, discounted and actual prices, discount percentages, ratings, rating counts, user IDs, image links, and product links. The notebook demonstrates how to handle missing values, remove special characters, transform data types, and split columns for better analysis. The cleaned dataset is saved for further use in data analysis or machine learning tasks.

# Key Features:

Data Cleaning: Removes special characters and handles missing values.

Data Transformation: Converts data types for numerical columns and splits the category column into main and subcategories.

Data Exploration: Provides initial insights into the dataset, including shape, data types, and missing values.

Automation: Automates repetitive tasks like removing special characters and converting data types.

Saving Cleaned Data: The cleaned dataset is saved as a CSV file for future use.

# Technologies Used:

Python

Pandas


# How It Works:

The dataset is loaded and inspected for initial insights.

Special characters are removed from columns like discounted_price, actual_price, and rating.

Data types are transformed for numerical columns to facilitate analysis.

The category column is split into Category and Sub Category for better organization.

Missing values are handled by replacing them with actual values from the source.

The cleaned dataset is saved as a new CSV file.

# Usage:

Clone the repository.

Run the notebook to clean and preprocess the dataset.

Use the cleaned dataset for further analysis or machine learning tasks.

This notebook is ideal for data scientists and analysts looking to preprocess Amazon product data efficiently.
