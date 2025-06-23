# Task1 (Data Cleaning and Preprocessing)
In this task, the following data cleaning operations were performed using Python (with pandas and numpy):

1. Identify and Handle Missing Values:<br>
Used .isnull().sum in Python to detect missing values.

2. Remove Duplicate Rows:<br>
Used .drop_duplicates() in pandas to eliminate duplicate records.

3. Standardize Text Values:<br>
As the table contained all unique values so no standardization was done.

4. Convert Date Formats:<br>
Unified all date fields to the format dd-mm-yyyy using pandas to_datetime() and string formatting.

5. Rename Column Headers:<br>
Renamed all column headers to lowercase and replaced spaces with underscores for consistency and readability.

6. Check and Fix Data Types:<br>
Ensured numerical columns like age are of int type and date columns are in datetime format.

7. Saved the final Cleaned Dataset:<br>
The final cleaned dataset ready for training was saved.


Libraries Used:

import pandas as pd  
import numpy as np

These steps ensure the dataset is clean, consistent, and ready for analysis or modeling.
