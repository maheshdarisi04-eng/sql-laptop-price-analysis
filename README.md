# Goal of the project
TO clean the unclead laptop price dataset and perform EDA on it using SQL.

# Project overview
Part A: Data Cleaning
1. Dropping non- imporatant columns using 'alter & drop'
2. Drop Null valuse using 'delete'
3. Changing data type of column using 'alter & modify column'
4. Processing one column into multiple columns following-
   a. Creating new columns using 'alter & add'
   b. Entering data into the created columns using 'update & set' and using 'case statements', 'replace', 'substring_index' on original column.
5. Dropping the original columns which are processed using 'alter & drop'.

Part B: EDA
1. Calculated statistical measures over price column using aggregate functions count, min, max, avg, std
2. Finding outliers in price column by calculating quartiles using 'percentile_cont' window function.
3. Plotted horizontal histograms for price categories using 'case statement', 'groupby'.
4. for categorical cols- value counts are generated visualised in excel using pie chart
5. for numerical categorical pair- compared distribution across categories using groupby
6. for pairs of numerical cols- scatterplots are generated
7. for pairs of categorical cols- contingency tables visualised in excel using stacked bar chart
8. feature engineering is done, created new columns using old columns.
9. one hot encoding is done using case statements

