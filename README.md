# Mastering Advanced Python: EV Data Analysis and Recommendation System
## Project Overview

This project focuses on analyzing an Electric Vehicle (EV) dataset using Python and statistical techniques to extract meaningful insights, identify patterns, perform hypothesis testing, and build a simple recommendation system. The objective is to demonstrate practical data analysis skills combined with business-oriented decision-making.

## Objectives
1. Analyze EV dataset to uncover key performance insights
2. Identify relationships between technical features
3. Detect anomalies using statistical methods
4. Build a recommendation system based on user preferences
5. Apply hypothesis testing to validate assumptions
6. Dataset Features

## The dataset includes the following attributes:

1. Car name, make, and model
2. Price and technical specifications
3. Battery capacity and driving range
4. Energy consumption
5. Engine power, torque, and performance metrics

## Key Tasks and Methodology

1. Filtering and Grouping

Filtered vehicles based on budget and range criteria, then grouped by manufacturer to calculate average battery capacity. This helps identify brands offering efficient and affordable EVs.

2. Outlier Detection

Used the Interquartile Range (IQR) method to detect anomalies in energy consumption. The analysis showed consistent consumption patterns with no significant outliers.

3. Correlation Analysis

Performed correlation analysis and visualization to study the relationship between battery capacity and driving range. A strong positive correlation was observed, indicating that higher battery capacity leads to longer range.

4. Recommendation System

Developed a Python class that recommends the top 3 EVs based on user-defined criteria such as budget, minimum range, and battery capacity. The system returns the most suitable vehicles based on performance.

5. Hypothesis Testing

Conducted an independent t-test to compare engine power between Tesla and Audi vehicles. The results indicated no statistically significant difference between the two groups.

# Key Insights
1. Battery capacity is a major factor influencing driving range
2. EV energy consumption is consistent across the dataset
3. Certain manufacturers provide better value for price and performance
4. Data-driven recommendations can support consumer decision-making
5. 
# Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Conclusion

This project demonstrates how data analysis and statistical techniques can be applied to real-world datasets to generate actionable insights. It also highlights the use of Python for building simple yet effective recommendation systems.

# Future Improvements
1. Integrate machine learning models for advanced recommendations
2. Develop an interactive dashboard using Power BI or Streamlit
3. Include more real-world datasets for better generalization
