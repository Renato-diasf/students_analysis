# Student Alcohol Consumption Analysis: Exploring Factors and Academic Performance

## Overview
This project analyzes the relationship between alcohol consumption among students and their academic performance, as well as other socio-demographic factors. The datasets used include information about students from two Portuguese schools, focusing on their grades, alcohol consumption, family background, and other relevant attributes. The goal is to identify patterns and correlations that may influence student behavior and academic outcomes.

## Datasets
The datasets used in this project are:
1. **Student Performance in Mathematics (`student-mat.csv`)**.
2. **Student Performance in Portuguese (`student-por.csv`)**.

Both datasets contain the following attributes:
- **Demographic Data**: Age, sex, address, family size, parents' education, etc.
- **Academic Data**: Grades (G1, G2, G3), study time, failures, etc.
- **Behavioral Data**: Alcohol consumption (weekday and weekend), going out with friends, etc.
- **Family Data**: Parents' cohabitation status, family support, etc.

## Project Structure
The analysis is divided into the following sections:

1. **Data Exploration**:
   - Understanding the structure of the datasets.
   - Handling missing values, duplicates, and outliers.

2. **Univariate Analysis**:
   - Exploring individual variables such as alcohol consumption, grades, and absences.
   - Visualizing distributions using histograms, box plots, and count plots.

3. **Bivariate Analysis**:
   - Investigating relationships between alcohol consumption and academic performance.
   - Analyzing correlations between variables such as study time, family background, and grades.

4. **Key Insights**:
   - Summarizing findings and drawing conclusions about the factors influencing student behavior and performance.

## Tools and Libraries
- **Python**: Primary programming language.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computations.
- **Seaborn**: Data visualization.
- **Matplotlib**: Additional plotting capabilities.

## Key Insights
1. **Alcohol Consumption**:
   - Higher alcohol consumption (both on weekdays and weekends) is negatively correlated with academic performance.
   - Male students tend to consume more alcohol than female students.

2. **Academic Performance**:
   - Students with higher study time and fewer past failures tend to perform better academically.
   - Access to the internet and aspirations for higher education positively influence grades.

3. **Family Background**:
   - Higher parental education levels are positively correlated with better student performance.
   - Family support and cohabitation status show minimal direct impact on alcohol consumption.

4. **Behavioral Factors**:
   - Students who spend more time going out with friends tend to consume more alcohol.
   - Alcohol consumption during weekdays is strongly correlated with consumption during weekends.

## How to Use This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-alcohol-consumption-analysis.git
