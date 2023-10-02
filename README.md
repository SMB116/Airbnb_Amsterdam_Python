# Week 2: Data Cleaning and Analysis with Pandas (Airbnb Dataset)

## Introduction
This GitHub README provides a summary of the Week 2 project for Intro to Numpy and Pandas. The project focuses on data cleaning and analysis using the Airbnb dataset. It covers various data cleaning tasks and concludes with some basic data analysis using Pandas.

### Notebook Link
You can access the project notebook on Google Colab by clicking [here](https://colab.research.google.com/drive/11wLBW5fQfdlxrtYlSnf2KiBh_IyWcFGW?usp=sharing).

### Streamlit App Link
To interact with the Streamlit app for visualizing the data, click [here](https://airbnbamsterdampython-bbebcda34uftuzhfrpaoou.streamlit.app/).

## Project Structure

1. **Downloading the Dataset**.

2. **Preprocessing the Dataset:** We begin by loading the downloaded files into Pandas DataFrames and then proceed with data cleaning tasks.

3. **Data Cleaning Tasks:** Here are some of the key data cleaning tasks performed:
   - Task 1: Reading Pickle and Parquet files.
   - Task 2: Displaying column names, types, and non-null values.
   - Task 3: Cleaning and formatting "discount_per_..." columns.
   - Task 4: Converting boolean columns.
   - Task 5: Formatting columns with currency symbols.
   - Task 6: Renaming specific columns.
   - Task 7: Converting "neighbourhood" and "room_type" to category types.
   - Task 8: Deleting irrelevant columns.
   - Task 9: Dropping rows with missing values in specific columns.
   - Task 10: Setting integer data type for "beds" and "bedrooms".
   - Task 11: Removing rows with empty "beds" and "bedrooms".

4. **Data Analysis:** Basic data analysis is performed in this section:
   - Task 15: Filtering listings with a minimum stay of 3 days and calculating the expected booking price for 5 days.
   - Task 16: Finding the maximum price and date for each listing.
   - Task 17: Merging the cleaned dataset with the calculated values.
   - Task 18: Grouping by "room_type" and finding the median values of "review_scores_rating" and "five_day_dollar_price".

## Conclusion
This README provides an overview of the project's structure and tasks. To explore the details, please refer to the project files. You can also download the final cleaned dataset for your own analysis. Feel free to extend and explore more with this dataset!
