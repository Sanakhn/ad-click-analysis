# Ad Click Analysis

## Overview
This project explores an online dataset to analyze patterns in ad clicks. The dataset includes demographic and behavioral features such as age, gender, device type, time of day, and whether a user clicked on an ad. The project focuses on data cleaning, distribution analysis, and identifying trends in click behavior across various factors.

## Technologies Used
- Programming Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn

## Dataset
The dataset contains the following features:
- Age: Age of the user
- Gender: Male, Female or Nonbinary
- Device Type: Desktop, Mobile, etc.
- Time of Day: Timestamp of the interaction
- Clicks: Binary value (1 = clicked, 0 = not clicked)
Link: https://www.kaggle.com/datasets/marius2303/ad-click-prediction-dataset

## Preprocessing Steps
Data Cleaning:
- Handled missing and inconsistent values.
- Standardized categorical features (e.g., gender, device type).

## Exploratory Data Analysis (EDA)
- Examined the distribution of clicks by gender.
- Visualized click-through rates (CTR) to identify trends.
- Analyzed the relationship between age groups and click behavior.
- Investigated peak ad engagement times.
- Categorized age into groups and calculated click rates for each.
- Explored differences in click behavior across device types.

## Results
Gender Trends:
- Males had a higher click-through rate than other groups.
Age Trends:
- Younger age groups showed higher engagement with ads, while older age groups clicked less frequently.
Time of Day Insights:
- Ads received the highest clicks during the morning and evening.
Device Insights:
- Mobile devices accounted for more clicks compared to desktops and tablets.

## Future Improvements
- Incorporate additional demographic and contextual features to enhance analysis.
- Use machine learning models to predict click behavior based on the dataset.
- Build an interactive dashboard to visualize real-time ad performance.
