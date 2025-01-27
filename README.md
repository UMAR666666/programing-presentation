# programing-presentation

### Umer Farooq Khan
###### Roll No : 139
###### BsAi 1C


## Summary of Steps

1. **Install Required Libraries**:
    - Installed `pandas`, `numpy`, `matplotlib`, and `seaborn` libraries.

2. **Import Libraries**:
    - Imported `pandas`, `numpy`, `matplotlib.pyplot`, and `seaborn`.

3. **Load Dataset**:
    - Loaded the lung cancer dataset from a CSV file into a pandas DataFrame.

4. **Data Inspection**:
    - Used `df.info()` to get a concise summary of the DataFrame.
    - Displayed the first few rows of the DataFrame using `df.head()`.
    - Checked the shape of the DataFrame using `df.shape`.
    - Displayed the last few rows of the DataFrame using `df.tail()`.

5. **Data Cleaning**:
    - Dropped the `Weight_Loss` column from the DataFrame.
    - Checked for missing values using `df.isnull().sum()`.
    - Dropped rows with missing values using `df.dropna(inplace=True)`.
    - Converted the `Tumor_Size_cm` column to integer type.
    - Renamed the `Age` column to `umer`.

6. **Data Visualization**:
    - Created a count plot of the `Gender` column using `sns.countplot()`.
    - Added bar labels to the count plot.
    - Created a count plot of `Gender` with `Age` as hue.
    - Created a pie chart of the `Gender` column value counts.

## Charts Summary

1. **Count Plot of Gender**:
    - Displayed the count of each gender in the dataset.

2. **Count Plot of Gender with Age as Hue**:
    - Displayed the count of each gender with different ages.

3. **Pie Chart of Gender**:
    - Displayed the distribution of gender in the dataset as a pie chart.







# Github Link 
https://github.com/UMAR666666/programing-presentation.git