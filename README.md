## Data Set is Available on the following link:##
https://drive.google.com/file/d/1mOvHtt5m4P_aLVnDv63Srag0HQUSayL7/view?usp=sharing

# Airbnb Exploratory Data Analysis (EDA)

## Introduction
Airbnb has transformed the way people travel by offering a variety of short-term rental options. As the platform grows, it is essential for hosts, guests, and Airbnb itself to understand the factors that contribute to a successful listing. This report presents an Exploratory Data Analysis (EDA) of Airbnb listings, aiming to uncover insights and trends that can help optimize listings.

## Purpose and Goals
The primary goal of this analysis is to explore Airbnb listings data and understand key factors such as pricing, availability, guest satisfaction, and market trends. This analysis addresses the following questions:
- How do prices vary across neighborhoods and room types?
- Which neighborhoods are the most popular, and why?
- How does listing availability change over time, and what affects it?
- What is the relationship between guest reviews and listing success?

## Scope of the Analysis
The dataset used in this analysis includes information from Airbnb listings across various neighborhoods and cities. Key focus areas include:
- **Location**: Performance of listings based on neighborhoods.
- **Time Period**: Multiple years of data to capture trends over time.
- **Key Features**: Room type, price, service fees, minimum stay requirements, number of reviews, availability, etc.

## How the Data Was Analyzed
The following steps were taken to perform the analysis:

1. **Data Cleaning**: Handled missing values, corrected data types, and removed outliers.
2. **Univariate Analysis**: Explored individual features such as price, room type, etc.
3. **Bivariate and Multivariate Analysis**: Examined relationships between features, like how neighborhood affects pricing or how reviews relate to success.
4. **Geographical Analysis**: Mapped listings to analyze spatial trends.
5. **Time Series Analysis**: Identified seasonal patterns in pricing and availability.

## Why This Analysis Matters
The insights gained from this analysis are valuable for:
- **Hosts**: Optimizing listing prices and improving guest satisfaction.
- **Guests**: Finding the best deals based on location and room type.
- **Airbnb**: Enhancing platform services by understanding market trends.
  
## Dataset Overview
The dataset used for this analysis is sourced from Kaggle's "New York City Airbnb Data Cleaning" project. It includes detailed information about Airbnb listings, reviews, and availability in New York City. 

### Data Description:
- **Listings**: Information such as location, price, room type, and availability for each Airbnb property.
- **Reviews**: Insights into guest satisfaction.
- **Calendar**: Tracks daily availability and pricing changes for each listing.

### Data Limitations:
The dataset only covers listings in New York City, and the findings may not generalize to other cities. Additionally, it represents a snapshot of the market and may not capture long-term trends.

## Data Cleaning Process
To prepare the dataset for analysis, the following steps were taken:

1. **Handling Missing Values**: Columns with extensive missing data (e.g., `License`, `House_rules`) were removed. Other missing values were handled by filling them with appropriate default values or removing rows with missing critical information.
2. **Outlier Detection and Treatment**: Unrealistic values, such as listings with over 2000 minimum nights, were removed.
3. **Data Type Conversion**: Columns were converted to appropriate data types (e.g., date columns were converted to datetime format).
4. **Renaming Columns**: Some columns were renamed for consistency and clarity.

## Data Exploration
### Overview
The dataset contains detailed information about the listings, such as price, availability, room type, and neighborhood. This phase provided a better understanding of the dataset's structure and content.

### Univariate Analysis
- **Price Distribution**: A histogram of prices shows the frequency of various price ranges, highlighting typical pricing strategies and detecting outliers.
- **Room Type Distribution**: Shows the proportion of different room types (e.g., entire home, private room) listed on Airbnb.

### Bivariate Analysis
- **Price vs. Neighborhood**: Analyzes how neighborhood affects the price of a listing.
  
### Multivariate Analysis
- **Correlation Heatmap**: Shows relationships between features such as price, availability, and reviews.

## Data Visualization
### Key Visualizations
1. **Price Distribution**: A histogram and boxplot were used to visualize the distribution of prices across neighborhoods and room types.
2. **Availability Across Neighborhoods**: A heatmap was created to show availability trends across neighborhoods.
3. **Geographical Distribution of Listings**: A scatter plot mapped the geographical distribution of Airbnb listings across New York City.
4. **Review Scores Distribution**: A violin plot was used to examine the distribution of review scores across room types and neighborhoods.

### Insights from Visualizations:
- **Pricing Trends**: Helps identify price ranges that are most common across room types and neighborhoods.
- **Availability Patterns**: Highlights neighborhoods with higher availability and demand.
- **Geographical Trends**: Shows popular areas for Airbnb listings.
- **Guest Satisfaction**: Reveals how room types and locations affect review scores.

## Conclusion
This analysis provides valuable insights into the Airbnb market in New York City. By analyzing key features such as pricing, availability, and reviews, we can better understand the factors that influence the success of an Airbnb listing. The findings from this analysis are useful for hosts, guests, and Airbnb itself to improve decision-making and optimize the platform’s functionality.

## Data
The dataset is sourced from Kaggle's "New York City Airbnb" data, consisting of over 100,000 observations. It contains information on listings, reviews, and availability in NYC.

### Dataset Information
- `Listings.csv`: Contains details about listings, including price, location, room type, and availability.
- `Reviews.csv`: Data on guest reviews, providing insight into customer satisfaction.

## Installation
To run this project locally, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/pythonophile/Airbnb-Data-Analysis.git
cd Airbnb-Data-Analysis
pip install -r requirements.txt

