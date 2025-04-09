Bangalore House Price Analysis
------------------------------

* Project Overview:
----------------
This project analyzes residential property prices in Bangalore, India, with a focus on price per square foot. The analysis includes exploratory data analysis, outlier detection and removal using various statistical methods, data normalization techniques, and correlation analysis among numerical features.

* Dataset:
----------
The dataset (house_price.csv) contains property listings from Bangalore with features such as:

Property size (in square feet)

-> Price

-> Location

-> Number of bedrooms/bathrooms

-> And other relevant property characteristics

* Analysis Components
---------------------
1. Exploratory Data Analysis
----------------------------
* Dataset shape and basic statistics

* Data types verification

* Missing values identification

* Distribution of price per square foot

* Summary statistics

2. Outlier Detection and Removal
--------------------------------
-> Four different methods were implemented and compared:

     * Mean and Standard Deviation Method: Identifying values beyond 3 standard deviations

     * Percentile Method: Filtering values outside 5th and 95th percentiles

     * IQR (Interquartile Range) Method: Removing values 1.5*IQR below Q1 or above Q3

     *  Z-Score Method: Removing values with absolute Z-scores greater than 3

-> For each method, two approaches were tested:

* Trimming: Complete removal of outlier records

* Capping: Replacing outliers with boundary values

3. Method Evaluation with Box Plots
-----------------------------------  
Box plots were used to visually compare the effectiveness of each outlier detection method, helping determine which approach best handles the data distribution characteristics.

4. Normality Testing and Transformations
----------------------------------------
* Original price per square foot distribution analysis

* Skewness and kurtosis measurement

* Statistical normality tests (Shapiro-Wilk or Kolmogorov-Smirnov)

  -> Transformations applied:

    * Logarithmic transformation
    * Square root transformation
    * Box-Cox transformation

* Comparison of normality metrics before and after transformations

5. Correlation Analysis
-----------------------
* Correlation matrix among all numerical features

* Heatmap visualization of correlations
  
*Identification of key relationships with price per square foot

6. Relationship Visualization
-----------------------------
* Scatter plots between price per square foot and most correlated features

*Visual identification of patterns and relationships

Requirements :
------------
* Python 3.x
* Libraries:

   * pandas
   * numpy
   * matplotlib
   * seaborn
   * scipy

Usage
-----
Clone the repository:

bashgit clone https://github.com/yourusername/bangalore-house-price-analysis.git
cd bangalore-house-price-analysis

Install required packages:

bashpip install -r requirements.txt

Run the analysis:

bashpython house_price_analysis.py

Results and Findings
--------------------
Key findings from the analysis include:

  * Distribution characteristics of property prices in Bangalore

  * Effectiveness of different outlier detection methods for real estate data

  * Most effective transformation for normalizing price data

  * Key factors correlated with property price per square foot

  *  Potential indicators for property valuation

Future Work
------------
* Develop predictive models based on the cleaned dataset

* Incorporate geospatial analysis to examine location impacts

* Segment analysis by property types and neighborhoods

* Time series analysis of price trends if temporal data is available

License
--------
MIT License

Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
