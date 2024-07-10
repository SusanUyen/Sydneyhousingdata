# Sydneyhousingdata

## Dataset Overview

- Number of Rows: 11,160
- Number of Columns: 17

## Purpose of the Dataset

This dataset explains various attributes of property sales in Sydney, such as price, date sold, suburb details, and property characteristics.

## Collection Details

- Why was it collected?
  The dataset was likely collected to analyze trends in the real estate market in Sydney, understand factors influencing property prices, and provide insights for buyers, sellers, and policymakers.
- Who paid for it?
  real estate companies, government agencies, or researchers. Specific information about the funding source is not provided.
- Where did you get it from?
  The dataset is from Kaggle, a platform for data science and machine learning competitions.
- Does it have a geographical component?
  Yes, the dataset includes geographical data, such as suburb names, latitude, longitude, and distance from the central business district (CBD).

## Column Descriptions

1. price

   - Description: Sale price of the property.
   - Measurement: Currency (AUD).
   - Data Type: Continuous.

2. date_sold

   - Description: Date when the property was sold.
   - Measurement: Date (DD/MM/YY).
   - Data Type: Categorical.

3. suburb

   - Description: Name of the suburb where the property is located.
   - Measurement: Text.
   - Data Type: Categorical.

4. num_bath

   - Description: Number of bathrooms in the property.
   - Measurement: Count.
   - Data Type: Continuous.

5. num_bed

   - Description: Number of bedrooms in the property.
   - Measurement: Count.
   - Data Type: Continuous.

6. num_parking

   - Description: Number of parking spaces in the property.
   - Measurement: Count.
   - Data Type: Continuous.

7. property_size

   - Description: Size of the property in square meters.
   - Measurement: Area (sqm).
   - Data Type: Continuous.

8. type

   - Description: Type of property (e.g., House, Vacant land).
   - Measurement: Text.
   - Data Type: Categorical.

9. suburb_population

   - Description: Population of the suburb.
   - Measurement: Count.
   - Data Type: Continuous.

10. suburb_median_income

    - Description: Median income of the suburb's population.
    - Measurement: Currency (AUD).
    - Data Type: Continuous.

11. suburb_sqkm

    - Description: Area of the suburb in square kilometers.
    - Measurement: Area (sqkm).
    - Data Type: Continuous.

12. suburb_lat

    - Description: Latitude coordinate of the suburb.
    - Measurement: Coordinate.
    - Data Type: Continuous.

13. suburb_lng

    - \*\*Description: Longitude coordinate of the suburb.
    - \*\*Measurement: Coordinate.
    - \*\*Data Type: Continuous.

14. suburb_elevation

    - Description: Elevation of the suburb in meters.
    - Measurement: Height (m).
    - Data Type: Continuous.

15. cash_rate

    - Description: Cash rate at the time of sale.
    - Measurement: Percentage.
    - Data Type: Continuous.

16. property_inflation_index:

    - Description: Inflation index of property values.
    - Measurement: Index.
    - Data Type: Continuous.

17. km_from_cbd
    - Description: Distance of the suburb from the central business district.
    - Measurement: Distance (km).
    - Data Type: Continuous.

Next, let's analyze each column to understand the data better.

## Column Analysis

### Categorical Columns

1. date_sold

   - Description: Date when the property was sold.
   - Measurement: Date (DD/MM/YY).
   - Data Type: Categorical.
   - Distribution: Varied distribution of sale dates.

2. suburb

   - Description: Name of the suburb where the property is located.
   - Measurement: Text.
   - Data Type: Categorical.
   - Distribution: Wide range of suburbs with varying frequency of sales.

3. type
   - Description: Type of property (e.g., House, Vacant land).
   - Measurement: Text.
   - Data Type: Categorical.
   - Distribution: Distribution between property types with houses being the most common.

### Continuous Columns

1. price

   - Description: Sale price of the property.
   - Measurement: Currency (AUD).
   - Data Type: Continuous.
   - Statistics:
     - Min: 225,000
     - Max: 60,000,000
     - Mean: 1,675,395
     - Median: 1,388,000
     - Std Dev: 1,290,371
   - Distribution: Skewed distribution with a few very high values.

2. num_bath

   - Description: Number of bathrooms in the property.
   - Measurement: Count.
   - Data Type: Continuous.
   - Statistics:
     - Min: 0
     - Max: 46
     - Mean: 2.07
     - Median: 2
     - Std Dev: 1.18
   - Distribution: Predominantly 1-3 bathrooms with a few outliers.

3. num_bed

   - Description: Number of bedrooms in the property.
   - Measurement: Count.
   - Data Type: Continuous.
   - Statistics:
     - Min: 0
     - Max: 47
     - Mean: 3.76
     - Median: 4
     - Std Dev: 1.56
   - Distribution: Predominantly 3-5 bedrooms with a few outliers.

4. num_parking

   - Description: Number of parking spaces in the property.
   - Measurement: Count.
   - Data Type: Continuous.
   - Statistics:
     - Min: 0
     - Max: 50
     - Mean: 2.02
     - Median: 2
     - Std Dev: 1.45
   - Distribution: Predominantly 1-2 parking spaces with a few outliers.

5. property_size

   - Description: Size of the property in square meters.
   - Measurement: Area (sqm).
   - Data Type: Continuous.
   - Statistics:
     - Min: 7
     - Max: 59,100
     - Mean: 723.01
     - Median: 600
     - Std Dev: 1,048.98
   - Distribution: Right-skewed with a few very large properties.

6. suburb_population

   - Description: Population of the suburb.
   - Measurement: Count.
   - Data Type: Continuous.
   - Statistics:
     - Min: 22
     - Max: 47,176
     - Mean: 9,311.56
     - Median: 7,457
     - Std Dev: 7,541.64
   - Distribution: Wide range of suburb populations.

7. suburb_median_income

   - Description: Median income of the suburb's population.
   - Measurement: Currency (AUD).
   - Data Type: Continuous.
   - Statistics:
     - Min: 14,248
     - Max: 97,500
     - Mean: 40,168.24
     - Median: 39,104
     - Std Dev: 11,089.96
   - Distribution: Normal distribution around the mean.

8. suburb_sqkm

   - Description: Area of the suburb in square kilometers.
   - Measurement: Area (sqkm).
   - Data Type: Continuous.
   - Statistics:
     - Min: 0.089
     - Max: 87.154
     - Mean: 5.05
     - Median: 3.566
     - Std Dev: 5.82
   - Distribution: Right-skewed with a few large suburbs.

9. suburb_lat

   - Description: Latitude coordinate of the suburb.
   - Measurement: Coordinate.
   - Data Type: Continuous.
   - Statistics:
     - Min: -34.10624
     - Max: -33.16376
     - Mean: -33.78141
     - Median: -33.80918
     - Std Dev: 0.202
   - Distribution: Clusters around certain latitudes.

10. suburb_lng

    - Description: Longitude coordinate of the suburb.
    - Measurement: Coordinate.
    - Data Type: Continuous.
    - Statistics:
      - Min: 150.55384
      - Max: 151.57333
      - Mean: 151.0967
      - Median: 151.1095
      - Std Dev: 0.213
    - Distribution: Clusters around certain longitudes.

11. suburb_elevation

    - Description: Elevation of the suburb in meters.
    - Measurement: Height (m).
    - Data Type: Continuous.
    - Statistics:
      - Min: 0
      - Max: 405
      - Mean: 55.61
      - Median: 40
      - Std Dev: 52.80
    - Distribution: Right-skewed with a few high-elevation suburbs.

12. cash_rate

    - Description: Cash rate at the time of sale.
    - Measurement: Percentage.
    - Data Type: Continuous.
    - Statistics:
      - Min: 0.1
      - Max: 2.0
      - Mean: 0.631
      - Median: 0.110
      - Std Dev: 0.659
    - Distribution: Bimodal distribution.

13. property_inflation_index

    - Description: Inflation index of property values.
    - Measurement: Index.
    - Data Type: Continuous.
    - Statistics:
      - Min: 150.9
      - Max: 220.1
      - Mean: 188.49
      - Median: 176.6
      - Std Dev: 24.44
    - Distribution: Normal distribution around the mean.

14. km_from_cbd
    - Description: Distance of the suburb from the central business district.
    - Measurement: Distance (km).
    - Data Type: Continuous.
    - Statistics:
      - Min: 0.31
      - Max: 84.79
      - Mean: 27.38
      - Median: 22.31
      - Std Dev: 18.47
    - Distribution: Right-skewed with many suburbs close to the CBD and a few far away.

## General Comments

- The dataset provides comprehensive information on property sales in Sydney, including price, property features, and geographical details.
- The distributions of continuous variables like price, property size, and distance from CBD are skewed, indicating the presence of outliers or high variability.
- The dataset includes both categorical and continuous data, making it suitable for various types of analysis, including time series and geographical mapping.

## Questions

- What are the trends in property prices in different suburbs of Sydney?
- How do property prices vary by the number of bedrooms and bathrooms?
- What is the average price of a property based on its distance from the CBD?
- How does the elevation of a suburb impact property prices?

Geographical Analysis

- Which suburbs have the highest and lowest property prices?
- How does the distance from the CBD influence property prices?
  What are the most common property types in different suburbs?
  How do property prices correlate with the geographical coordinates (latitude and longitude) of suburbs?
  Demographic Analysis

How does the median income of a suburb's population affect property prices?
Is there a correlation between suburb population size and property prices?
Which suburbs have seen the most growth in property prices over time?
Property Features Analysis

How does the size of the property (in square meters) impact its price?
What is the distribution of properties with different numbers of bedrooms and bathrooms?
How do the number of parking spaces available affect property prices?

Temporal Analysis

What are the seasonal trends in property sales in Sydney?
How have property prices changed over the years?
Are there specific times of the year when properties are sold at higher or lower prices?
Economic Factors

How does the cash rate at the time of sale impact property prices?
What is the relationship between the property inflation index and property prices?

## Questions to Challenge Viewer Assumptions

Suburb Popularity

Are the most expensive suburbs always the most desirable to live in?
How does the desirability of a suburb change with factors like population density and median income?
Investment Potential

Which suburbs offer the best investment potential based on price trends and growth rates?
Are there undervalued suburbs that are likely to see price increases in the near future?
Impact of Features

How significant is the impact of property features (e.g., number of bedrooms, bathrooms, parking spaces) on the overall price?
Are larger properties always more expensive, or is there a diminishing return on size?
Economic Conditions

How do changes in the cash rate influence the real estate market?
What external economic factors might be driving changes in property prices?
Geographical Preferences

How do geographical preferences (e.g., proximity to CBD, elevation, coordinates) influence the market?
Are there emerging suburbs that are becoming more popular due to geographical or economic factors?
