# solar-energy-analytics
Solar energy is one of the most popular renewable energy sources on the planet, and its popularity is growing. The current study predicts the production of horizontal photovoltaics installed in 12 places across the northern hemisphere. Without irradiance information, just location and weather data are used. While irradiance is a good predictor of solar power generation, gathering this data about a site can be time-consuming, and estimations can be inaccurate. As a result, the capacity to predict power production without irradiance data needs to be investigated further in order to save time, effort, and money while maintaining accuracy.

# Dataset
The data is publicly available on Kaggle and consists of 14 months of power output, location, and weather data. The remaining sections will cover data processing, modeling, results, and conclusions.

## Data Preprocessing
The dataset consists of 21,045 rows and 17 columns. Let’s explore the available columns in the dataset using functions in pandas- Python data analysis library.

# Feature engineering
Here, create new features from existing ones to make categorical variables usable in our machine learning algorithms and also capture more patterns in the data.
First, we perform the encoding of categorical variables namely location and season using the one-hot encoding method.

# Conclusions
Standard data science techniques have been applied to predicting the solar power output in 12 different locations. The results show that KNN is the best base model while the stacked model gave the overall best performance.
The best model may be further trained for individual locations to achieve even better scores however, that is not covered in this analysis.
Finally, the approach followed in this work can be used as a standard procedure to solve predictive analytics problems in the renewable energy space.
