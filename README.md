Mobile App Data Analysis
Project Overview
This project involves analyzing a dataset of mobile apps to uncover insights related to app categories, pricing strategies, user ratings, and sentiment analysis of user reviews. The analysis includes data cleaning, data type correction, visualization of app distributions, and sentiment evaluation. The dataset provides a comprehensive overview of app performance and user feedback.

Data Description
Dataset: Google Play Store Apps
Key Columns:
App: Name of the app
Category: Category of the app
Rating: App rating (1-5)
Reviews: Number of reviews
Size: App size in MB
Installs: Number of installs
Type: Free or Paid
Price: Price of the app
Tasks Completed
1. Data Cleaning
Special Characters Removal: Removed special characters from Installs and Price columns.
Data Type Correction: Converted Installs and Price columns to float type.
2. Data Visualization
App Distribution by Category: Created a bar chart to show the distribution of apps across different categories.
App Rating Distribution: Plotted a histogram to visualize the distribution of app ratings and added an annotation for the average rating.
Size and Price Analysis: Examined the relationship between app size, price, and rating using joint plots.
App Pricing Trend: Used a strip plot to visualize the distribution of paid apps across different categories.
Junk Apps Filtering: Filtered out apps priced above $100 and re-visualized the price distribution.
Paid vs. Free Apps: Compared the number of installs for paid vs. free apps using a box plot.
Sentiment Analysis: Analyzed user reviews to compare sentiment polarity between paid and free apps.
Insights
Category Trends: Identified which categories have the highest and lowest number of apps.
Rating Trends: Observed that most top-rated apps have a size between 2 MB and 20 MB.
Pricing Strategy: Found that Medical and Family apps are generally more expensive, while Game apps are priced below $20.
Sentiment Analysis: Revealed that paid apps generally receive more positive reviews compared to free apps.
Requirements
Python Packages:
pandas
numpy
seaborn
matplotlib
plotly
Usage
Load the Dataset: Load the dataset using pandas.
Perform Data Cleaning: Clean and preprocess the data as outlined in the tasks.
Generate Visualizations: Use seaborn, matplotlib, and plotly for various visualizations.
Analyze Results: Review the generated plots and insights to draw conclusions about the app data.
