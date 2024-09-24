Data Cleaning and Preprocessing

Overview

This project involves cleaning and preprocessing a customer dataset from the banking domain, ensuring it is ready for further analysis and modeling.

Steps Taken

Renamed Columns: All column names were standardized for clarity and consistency.

Handled Outliers: Outliers were identified and removed using the unique() function, with rows containing extreme values being dropped.

Corrected Data Types: All columns were converted to their appropriate data types for accurate analysis.

Managed Missing Values:
Columns with more than 90% missing values were removed.
Rows with significant missing values were evaluated and removed if necessary.
Considered techniques like mean imputation, but unique missing values were removed when they couldn’t be replaced meaningfully.
Removed Non-informative Columns: Columns with only one unique value were removed as they did not add value to the analysis.

Outcome

The dataset has been cleaned and is now ready for further exploration and modeling.

