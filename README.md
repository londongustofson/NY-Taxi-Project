# NY-Taxi-Project

Link to Kaggle: https://www.kaggle.com/c/new-york-city-taxi-fare-prediction
Link to raw data: https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/data (use train.csv)
Hourly daily weather data: https://www.kaggle.com/selfishgene/historical-hourly-weather-data#temperature.csv
Sampled data from train.csv that used in analysis: https://drive.google.com/open?id=1i3RV5OCx57AECJNRgIbDqng9p0lKB-r8
Descriptions of files

NYTaxi_data_cleaning_gcp.ipynb: this file runs on Google Cloud that cleans the raw data from Kaggle and exports a sampled file which composes 25% of the cleaned data
NYTaxi_manipulation_gcp.ipynb: this file runs on Google Cloud that transform and adding additional variable for analysis
NYTaxi_analysis_local.ipynb: this is the actual data analysis code runs on Jupyter Notebook offline
Plot: stores the heatmap that presents the distribution of pick-up and drop-off location. THe html file in Plot only used partial data since the full data is too big
