# Data Imputation Program (Version 3.4)

This program is designed for imputing missing values in a dataset using various machine learning methods. It focuses on multivariate imputation techniques and is intended for use with the "AMR-and-NSH-Buoy-Data1394-Clean-Data.xls" dataset. The program utilizes the scikit-learn library for machine learning and pandas for data manipulation.

## Instructions

1. **Requirements:**
   - Ensure you have the required Python libraries installed, including pandas, seaborn, and matplotlib.

2. **Dataset:**
   - Make sure you have the dataset "AMR-and-NSH-Buoy-Data1394-Clean-Data.xls" in the same directory as this script. This dataset should contain the data you want to impute.

3. **Run the Script:**
   - Run the Python script `main.py` using your preferred Python interpreter. There's no need to include "python main.py" in the command.

4. **Output:**
   - The program will perform the following steps:
     - Load the dataset.
     - Find the number of missing values in each column.
     - Separate data for "Buoy Amirabad" and "Buoy Noshahr."
     - Normalize the data.
     - Generate synthetic datetime values.
     - Use DecisionTreeRegressor for imputation.
     - Save the imputed dataset as a CSV file in the "multivariate-method-results" directory.

5. **Results:**
   - The imputed dataset will be saved as a CSV file, e.g., "AMR-and-NSH-Buoy-Data1394-normalized-mice-decision-tree-regressor.csv," in the "multivariate-method-results" directory.

6. **Data Analysis:**
   - The program also provides data analysis, such as Seaborn distribution plots for specific columns. You can modify the code to perform additional analyses as needed.

7. **Customization:**
   - You can customize the program by adjusting parameters, changing the estimator used for imputation, or adding more data analysis steps as required.

8. **Version Information:**
   - This is Version 3.4 of the program. It utilizes DecisionTreeRegressor for imputation.

## Note

- Ensure that the necessary libraries and dataset are available before running the program.
- You can modify the program to use different machine learning models or parameters to suit your specific imputation needs.
