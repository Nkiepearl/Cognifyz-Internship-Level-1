# Restaurant Data Analysis

## Table of Contents
- [Description](#description)
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Business Problem](#business-problem)
- [Project Objective](#project-objective)
- [Steps Followed](#steps-followed)
- [Tools](#tools)
- [Findings](#findings)
- [Note](#note)

### Description
This project focuses on analyzing restaurant data to uncover key insights related to cuisine popularity, city-wise distribution, price range trends, and online delivery services.

### Project Overview
The analysis includes:

- Identifying the most common cuisines and their prevalence.
- Examining restaurant distribution and ratings across different cities.
- Understanding the distribution of price ranges among restaurants.
- Investigating the impact of online delivery services on restaurant ratings.

By leveraging data analytics, this project aims to provide valuable insights for restaurant owners, food delivery platforms, and stakeholders in the food industry.

### Data Source
The dataset used in this project was sourced from Cognifyz internship programme. It contains restaurant details, including cuisine type, location, ratings, price range, and online delivery availability.

### Business Problem
Restaurants and food delivery platforms need data-driven insights to optimize menu offerings, expansion strategies, pricing models, and service options. Key challenges include:

- Identifying the most popular cuisines to cater to customer demand.
- Determining the best cities for restaurant expansion based on density and ratings.
- Understanding price trends to position restaurants effectively in the market.
- Evaluating the impact of online delivery services on customer satisfaction and business performance.

### Project Objective
- Cuisine Analysis: Identify the top three most common cuisines and their distribution across restaurants.
- City Analysis: Determine the city with the highest number of restaurants and analyze average ratings per city.
- Price Range Distribution: Visualize price categories among restaurants and calculate the percentage of restaurants in each range.
- Online Delivery Impact: Analyze the percentage of restaurants offering online delivery and compare their average ratings with non-delivery restaurants.

### Steps Followed
1. Data Loading: Imported the dataset and performed an initial inspection to understand its structure.

2. Data Cleaning: Handled missing values, duplicates, and ensured data consistency.

3. Cuisine Analysis:

Identified the top three most common cuisines:

- North Indian: 2,992 restaurants
- Chinese: 1,880 restaurants
- Fast Food: 1,314 restaurants

4. City Analysis:

Determined the city with the highest number of restaurants: New Delhi.

Analyzed city-wise average ratings:

- Highest-rated city: Inner City (highest average rating).
- Sample city-wise ratings:
- Istanbul: 4.29
- Abu Dhabi: 4.30
- Agra: 3.97
- Ahmedabad: 4.16

5. Price Range Distribution:

Created visualizations (histograms, bar charts) to show the distribution of restaurants across different price categories.

Distribution percentages:

- Budget (1-star restaurants): 46.53%
- Mid-range (2-star restaurants): 32.59%
- Premium (3-star restaurants): 14.74%
- Luxury (4-star restaurants): 6.14%

6. Online Delivery Impact:

- Percentage of restaurants offering online delivery: 25.66%
- Comparison of average ratings:
- With online delivery: 3.25
- Without online delivery: 2.47

### Tools
- Programming Language: Python
- Libraries Used: Pandas, NumPy, Matplotlib, Seaborn
- Data Visualization: Bar Charts, Pie charts
- Data Processing: Pandas DataFrames for filtering and aggregating data

### Findings
Top Three Cuisines:

- North Indian: 2,992 restaurants
- Chinese: 1,880 restaurants
- Fast Food: 1,314 restaurants

City Analysis:

- The city with the highest number of restaurants is New Delhi.
- The highest-rated city is Inner City.

Average Ratings per City:

- Istanbul: 4.29
- Abu Dhabi: 4.30
- Agra: 3.97
- Ahmedabad: 4.16

Price Range Distribution:

- Budget (1-star restaurants): 46.53%
- Mid-range (2-star restaurants): 32.59%
- Premium (3-star restaurants): 14.74%
- Luxury (4-star restaurants): 6.14%

Online Delivery Impact:

- Percentage of restaurants offering online delivery: 25.66%
- Comparison of average ratings:
- Restaurants with online delivery: 3.25
- Restaurants without online delivery: 2.47

### Note
For a better understanding, visualizations have been included in the analysis:

- Cuisine distribution (Bar chart)
- City-wise ratings (Histogram)
- Price range distribution (Pie chart)
- Online delivery impact on ratings (Boxplot)
