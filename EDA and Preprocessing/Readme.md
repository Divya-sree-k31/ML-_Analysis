# EDA and Data Preprocessing Project

## Objective
This project implements a robust data preprocessing system that addresses common data challenges such as missing values, outliers, inconsistent formatting, and noise. By performing effective data preprocessing, the project enhances the quality, reliability, and usefulness of the dataset for machine learning applications.

## Dataset
The project uses a health dataset containing information about patients, including demographic information and various health parameters.

## Components and Implementation

### 1. Data Exploration (Score: 2)
- **Unique Value Analysis**: Identified and listed unique values in each feature along with their counts
- **Statistical Analysis**: Generated comprehensive descriptive statistics for all numerical features
- **Column Renaming**: Improved column naming for better readability (where applicable)

### 2. Data Cleaning (Score: 2)
- **Missing Value Detection**: Identified and highlighted columns with missing values
- **Inappropriate Value Handling**: Detected and addressed inconsistent or inappropriate data entries
- **Duplicate Removal**: Identified and removed duplicate records from the dataset
- **Outlier Detection**: Used Interquartile Range (IQR) method to identify outliers in numerical columns
- **Special Case Handling**: Replaced zero values in age column with NaN values
- **Null Value Treatment**: Applied appropriate methods (mean/median/mode) based on data type to handle missing values

### 3. Data Analysis (Score: 2)
- **Conditional Filtering**: Created subset of data with age > 40 and salary < 5000
- **Visualization**: Generated plots to explore relationships between age and salary
- **Distribution Analysis**: Counted and visualized the number of people from each location/category using both bar charts and pie charts

### 4. Data Encoding (Score: 2)
- **Label Encoding**: Applied Label Encoding to convert categorical variables into numerical representations
- **One-Hot Encoding**: Implemented One-Hot Encoding to create binary columns for categorical variables
- **Encoding Comparison**: Preserved both encoding approaches to demonstrate differences in the resulting data structure

### 5. Feature Scaling (Score: 2)
- **StandardScaler**: Applied StandardScaler to normalize features (mean=0, std=1)
- **MinMaxScaler**: Applied MinMaxScaler to scale features to a specific range (0 to 1)
- **Visualization**: Created comparative visualizations to demonstrate the effects of different scaling methods
- **Statistical Comparison**: Analyzed the statistical properties of the data before and after scaling

## Key Findings
- The dataset contains both numerical and categorical features requiring different preprocessing approaches
- Outliers were identified in several numerical columns using the IQR method
- Categorical features were successfully encoded using both Label Encoding and One-Hot Encoding
- Feature scaling significantly normalized the data distribution, making it more suitable for machine learning algorithms

## Conclusion
The preprocessing pipeline successfully transformed raw data into a clean, structured format appropriate for machine learning applications. Different encoding and scaling methods were applied and compared, providing insight into their effects on the dataset's properties. The final preprocessed dataset is now ready for feature selection, model training, and evaluation.

## Tools and Technologies
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## Usage
1. Install required libraries: `pip install pandas numpy matplotlib seaborn scikit-learn`
2. Place the dataset file in the same directory as the script
3. Run the script: `python eda_preprocessing.py`
