# Zomato Restaurant Data Analysis

### Cognifyz Technologies — Data Science Internship

## Project Overview

This project performs exploratory data analysis on the Zomato
restaurant dataset to identify meaningful patterns related to:

- Restaurant distribution
- Cuisine preferences
- Customer ratings
- Pricing
- Online delivery
- Table booking
- Customer engagement
- City-wise restaurant performance

The goal is to transform raw restaurant data into actionable business
insights using Python-based data analysis and visualization.

## Objectives

- Understand the structure of the Zomato dataset.
- Clean and preprocess the dataset.
- Analyze restaurant distribution across cities.
- Identify popular cuisines.
- Analyze restaurant ratings.
- Study price ranges and average cost.
- Analyze online delivery availability.
- Analyze table booking availability.
- Examine the relationship between ratings and votes.
- Perform correlation analysis.
- Generate business insights and recommendations.

## Dataset

The dataset contains:

- **9,551 restaurant records**
- **21 attributes**

Important features include:

- Restaurant ID
- Restaurant Name
- City
- Locality
- Cuisines
- Average Cost for two
- Has Table booking
- Has Online delivery
- Price range
- Aggregate rating
- Rating text
- Votes

## Data Cleaning

The dataset was checked for:

- Missing values
- Duplicate records
- Data types
- Numerical and categorical variables

The dataset initially contained **9 missing values in the Cuisines
column**.

These missing values were handled during preprocessing.

## Exploratory Data Analysis

The project investigates:

### Restaurant Distribution

Analysis of the cities with the highest number of restaurants.

### Cuisine Analysis

Identification of the most frequently offered cuisines.

### Rating Analysis

Analysis of:

- Aggregate rating
- Rating categories
- Rating distribution

### Price Analysis

Analysis of:

- Price range
- Average cost for two
- Relationship between price and rating

### Service Analysis

Analysis of:

- Online delivery
- Table booking
- Service availability versus ratings

### Customer Engagement

Analysis of:

- Votes
- Ratings
- Relationship between votes and ratings

## Correlation Analysis

Correlation analysis is used to examine relationships between
numerical variables such as:

- Average Cost for two
- Price range
- Aggregate rating
- Votes
- Latitude
- Longitude

The correlation matrix helps identify positive, negative, and weak
relationships between numerical variables.

## Key Insights

The analysis identified several important patterns:

1. Restaurant distribution varies significantly across cities.
2. A limited number of cuisines account for a large proportion of
   restaurant offerings.
3. Restaurant ratings are concentrated within specific rating ranges.
4. Average cost generally increases with restaurant price range.
5. Online delivery availability varies considerably among restaurants.
6. Table booking availability differs across restaurant segments.
7. Customer votes provide an indication of customer engagement.
8. Pricing and customer ratings can be compared to understand
   restaurant positioning.
9. City-level analysis reveals differences in restaurant performance.
10. Correlation analysis provides quantitative information about
    relationships between numerical variables.

## Business Recommendations

### Pricing Strategy

Restaurants should balance pricing with customer-perceived value.

### Digital Services

Restaurants should evaluate online delivery based on customer demand.

### Customer Experience

Regular monitoring of ratings and customer feedback can help identify
service-quality issues.

### Location Strategy

Businesses should consider restaurant density, competition, cuisine
demand, and ratings when evaluating locations.

### Cuisine Strategy

Popular cuisines can indicate strong customer demand, while less
represented cuisines may provide opportunities for differentiation.

### Customer Engagement

Restaurants should monitor both ratings and customer engagement
metrics such as votes.

## Limitations

- The dataset represents information from a specific period.
- Customer ratings are subjective.
- Correlation does not imply causation.
- Detailed customer demographics are unavailable.
- Operational factors such as waiting time and food quality are not
  directly available.
- Restaurant representation varies between cities.
- Cost comparisons across countries may be affected by currency
  differences.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

```text
Data Collection
      ↓
Data Loading
      ↓
Data Understanding
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Data Visualization
      ↓
Statistical Analysis
      ↓
Correlation Analysis
      ↓
Business Insights
      ↓
Recommendations
      ↓
Conclusion