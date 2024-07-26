# Chapter 3: Methodology 

Data Science Project Life Cycle 
The Illustration of the data science project life cycle are: 

## 3.1. Problem Definition: 

The research problem investigated in this study is predicting traffic congestion in Malaysia using machine learning algorithms. The goal is to develop models that can accurately forecast traffic jams, enabling better traffic management and planning.

## 3.2. Data Collection: 

### 3.2.1. Accessing Traffic Data from Xmap.ai: API Registration: Registered for an API key on the Xmap.ai platform API Requests: Utilizing the API key, perform HTTP GET requests to the Xmap.ai endpoints to get traffic data. The data get in JSON format and contains various traffic metrics. Data Storage: Stored the collected data in CSV , to process it in the analysis step. 
2. Fetching Weather Data from OpenWeatherMap: API Registration: Signed up for an API key on the OpenWeatherMap website API Requests: Use the API key to make requests to the OpenWeatherMap historical weather data endpoint. 

### 3.2.2 Obtaining Public Transport Ridership and Vehicle Registration Data: Data Download: Navigate to the Ministry of Transport, Malaysia's open data portal and acquire the datasets. These are dataset files in CSV format. Data Import: Import the downloaded CSV files into an analysis environment using a variety of data manipulation libraries. Data Cleaning: The dataset will prospectively require cleaning to account for incomplete data and inconsistencies, all of which can influence the accuracy of any further data handling.

### 3.2.3 Data Preprocessing: 

The collected data will be thoroughly cleaned to ensure accuracy. This involves imputing any missing or null values, converting different time formats to a uniform standard, and incorporating new derived features. This step is crucial to prepare the data for effective analysis and modeling.

### 3.2.4. Exploratory Data Analysis (EDA):
Comprehensive visualization and analysis of the data will be conducted using graphical libraries. This step will help identify important patterns, trends, and insights within the data. Graphical representations will make it easier to understand the data’s behavior and identify any anomalies or significant trends.

### 3.2.5. Model Evaluation: 
Machine learning models will be developed and trained to gain insights and learn complex patterns in the dataset. This involves selecting appropriate algorithms, tuning model parameters, and training the models on the preprocessed data to ensure they can accurately predict traffic congestion.

### 3.2.6. Deployment and Monitoring: 
The final stage involves implementing the best-performing model in a production environment and monitoring its behavior. This ensures the model continues to perform well with new data and can provide real-time traffic predictions. Ongoing monitoring will help detect any issues and allow for timely updates to the model as needed.

 <p align="center">
<img src="https://github.com/drshahizan/research-design/blob/main/proposal/LURUIQI7/Chapter5/1.png?raw=true"  height="400" />
</p>

<p align="center">
Figure : Data Science Project Life Cycle
</p>

Figure : Data Science Project Life Cycle
Data Sources and Collection Methods 
1. Traffic Volume Data: It's the data get from traffic sensors, cameras, or data found online from government transportation agencies. 
2. Weather Data: The data is acquired from an external API like OpenWeatherMap, weather source website providing historical weather data. 
3. Public Transportation Ridership Data: Data can be collected from public transportation agencies or through any open data website related to transportation. 
4. Historical Accident Data: The data here can be gathered from, police reports or crash data reports from governing bodies or transportation related agencies. 
Data Pre-processing 
This stage is crucial as it ensures none of the data used is dirty or flawed before further analysis, and the involvement of data preprocessing consist of the following: 
1.Data Cleaning: - Handling Missing Values: Null values can be filled in by several methods and techniques. Like: imputing mean, median, or mode for numerical data, and the use of the most frequent category for categorical. - Outliers Removal: To detect and remove outliers, statistical methods such as Z-score and IQR should be used as outliers can have a major impact on data distribution. 
2.Data Transformation: - Normalization: Scale numerical features to a standard range, typically between 0 and 1, after which all features will be equally contributing towards model learning. Techniques: Min-Max Scaling, Standard Scaler. - Encoding Categorical Variables: Transformation of categorical data to numerical quantities. Techniques: One-Hot Encoding, Label encoder. 
3. Feature Engineering: Creating New Features: Generation of other features from given data. Examples: time of day, traffic density, road occupancy, time-travel distance impact, and the cumulative weather scores. - Feature Selection: Choose which relevant features to use. Methods: correlation, Mutual Information score, feature importance scores from Random Forest, etc. 
First Exploratory Data Analysis and Results 
1. Traffic Volume Over Time: Line plots of how the traffic volume changes every hour and every day of the week. 
2. Heatmaps: Correlation matrices of various features and their relationship with the traffic volume. 
3. Descriptive Statistics: Mean, median, standard deviation, and range for the traffic volume and other numerical features. 
Initial Machine Learning Models 
1. Linear Regression: As a naive model to predict the traffic volume. Performance Metrics: Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). 
2. Random Forest: Consider non-linear interactions between different predictors. Performance Metrics: MAE, RMSE, R-squared. 
3. Gradient Boosting: Ensemble method combining multiple weak learners which combines things well to improve overall performance. Performance Metrics: MAE, RMSE, R-squared.
