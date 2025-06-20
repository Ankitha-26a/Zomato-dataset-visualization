#### Zomato-dataset-visualization
## Introduction 
This project focuses on analyzing Zomato restaurant data specifically from Bengaluru, India. It explores various aspects of the city's food and dining scene, including the availability of online orders, table booking options, types of restaurants (like cafes, pubs, delivery, dine-out, etc.), and customer ratings. The analysis uses Python with libraries such as Pandas, Seaborn, and Matplotlib to visualize trends and extract actionable insights. The goal is to identify the most popular service types, high-demand locations, and restaurant categories to assist stakeholders in making strategic decisions within Bengaluru’s dynamic food industry.

# Data Preprocessing
Cleaning specific columns like ratings, restaurant types, and costs

# Visualization
Using `matplotlib` and `seaborn` for visualizing relationships and distributions across various restaurant features.

## Dataset
The dataset used in this project is Zomato restaurant data, which contains information like restaurant names, locations, cuisines, ratings, and more.

**Columns used**:
- Restaurant name
- Location
- Online order availability
- Booking table facility
- Ratings, Votes
- Cuisines, etc.

## Exploratory Data Analysis
 start by understanding the dataset with:
  - Checking dataset shape and columns.
  - Displaying the first few records using `data.head()`.

## Data Cleaning
Data cleaning steps include:

 - Dropping redundant columns such as URL, address, phone number, etc.
 - Handling missing values in the `rate` column by removing unwanted characters and filling missing values with the mean rating.
 - Cleaning other columns like `cost2plates`, `location`, `rest_type`, and `cuisines` to ensure data consistency.

## Data Visualization
Using `matplotlib` and `seaborn`, we visualize key insights:

  - Count of restaurants per location.
  - Availability of online ordering and table booking facilities.
  - Restaurant types and their ratings.
  - Distribution of votes across different locations and cuisines.

Sample visualizations include:

  - Count plots of restaurant locations.
  - Boxplots comparing online ordering facilities with ratings.
  - Bar charts for location-based restaurant facilities and vote counts.

## Conclusion
This project provided insights into various features of restaurants in the dataset. By cleaning and visualizing the data, we observed patterns related to restaurant ratings, the availability of online orders, and location-specific trends. These insights could help users in making informed decisions about their dining preferences.






