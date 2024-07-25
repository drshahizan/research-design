## Chapter 3: Methodology
## 3.1 Research design
This study uses a quantitative research design to analyze figures and data visualization to produce results to give recommendations. Quantitative methods are well suited to the application of this study as it involves analyzing large data sets to identify patterns, trends and relationships in supply chain operations. Specific methods include descriptive statistics, predictive modeling and machine learning techniques.
![image](https://github.com/user-attachments/assets/70385568-873c-46ad-a68f-aecf525f3be0)


## 3.2 Data collection and pre-processing
Data source: supply store dataset from Github
https://github.com/drshahizan/dataset/tree/main/mongodb/01-sales
Data cleaning: data was imported and cleaned to ensure accuracy and completeness, resolve missing values, inconsistencies, and outliers, standardize date formats and ensure consistency of categorical data, and create relevant variables for analysis.

<img width="258" alt="data" src="https://github.com/user-attachments/assets/b44f48cd-e49d-4fe0-9f6e-485aaf33470c">

## 3.3 Exploratory Data Analysis (EDA)
Descriptive statistics: use Python libraries such as Pandas and NumPy to calculate metrics such as mean, median, standard deviation, and distribution for key variables (e.g., sales, volume, customer satisfaction).
Visualization: Use histograms, bar charts, and box-and-line plots using Matplotlib and Seaborn to visualize other key metrics such as sales trends, seasonal patterns, product popularity, and customer demographics.
Correlation analysis: the Pearson correlation coefficient is used to identify relationships between variables such as sales volume, customer satisfaction and buying patterns to inform the predictive model.

## 3.4 Forecasting Modeling
Demand forecasting: time series analysis using ARIMA and exponential smoothing models to forecast future sales based on historical data. These analyses are performed using Python's tatsmodels library.
Inventory optimization: machine learning algorithms such as Random Forest and XGBoost are applied to recommend optimal inventory levels and reorder points. Scikit-learn and XGBoost libraries are used.
Customer Segmentation : Cluster analysis using K-means or hierarchical clustering to develop customer segmentation models by clustering customers based on purchase behavior and demographics.Scikit-learn library is used for clustering.

## 3.5 Model evaluation and validation
Cross-validation: k-fold cross-validation is used to assess the model performance to ensure robustness and prevent overfitting.
Evaluation metrics: metrics such as Mean Absolute Error (MAE), Root Mean Square Error (RMSE) and Accuracy are used to evaluate model predictions. These are calculated using Python libraries such as Scikit-learn and Statsmodels.

## 3.6 Software and analytic frameworks
Python: the main programming language used for data analysis, containing libraries such as Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels and XGBoost.
Jupyter Notebooks: for interactive data analysis and visualization.
Power BI: for data visualization of analysis results.


