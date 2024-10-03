# Exploratory Data Analysis (EDA) on Aspiring Minds Employment Outcome Dataset

# Project Overview

This project involves performing Exploratory Data Analysis (EDA) on the Aspiring Minds Employment Outcome 2015 (AMEO) dataset.
# Objective
- Perform exploratory data analysis on the dataset and gain insights.
- Analyze salary trends across job roles, specializations, gender, and AMCAT scores.
- Test claims made in research articles about salary trends for fresh graduates in certain job roles.
- Identify relationships between different categorical and numerical variables.
  
# Steps Involved
1. Data Import and Cleaning : Load the dataset, handle missing values, and ensure the correct data types for each variable.
2. Univariate Analysis:
   - Analyze individual variables like salary, AMCAT scores, academic scores, gender distribution, and specialization.
   - Use histograms, boxplots, and count plots to visualize the distribution of these variables.
3. Bivariate Analysis:
   - Analyze relationships between variables using scatter plots, pair plots, boxplots, and bar plots.
   - Explore relationships between salary and factors like AMCAT scores, academic performance, and specialization.
   - Examine the influence of gender on specialization and salary.
4. Outlier Detection: Identify outliers in salary and AMCAT scores using boxplots.
5. Research Questions:
   - Test salary trends for fresh graduates in specific job roles like Software Engineer, Programmer Analyst, etc.
   - Analyze if there is a relationship between gender and specialization.
   - 
# Results & Key Insights

1. Salary Distribution:
   - Salaries are right-skewed with most candidates earning between 200,000 and 300,000 INR.
   - Several outliers exist in the salary distribution, with a few candidates earning much higher than the rest.
   
2. AMCAT Scores:
   - Most AMCAT scores are well-distributed, but some outliers exist in certain sections.
   - There is no clear linear relationship between AMCAT scores and salary.

3. Gender and Specialization:
   - Male candidates dominate specializations like Mechanical and Civil Engineering, while female candidates are more prevalent in Computer Science and Information Technology.

4. Job Roles and Salary:
   - Fresh graduates in roles like Software Engineer and Associate Engineer tend to have higher median salaries compared to other roles like Technical Support Engineer.
   - The claim that fresh graduates in roles like Software Engineer earn around 250,000-300,000 INR is supported by the data.

# Tools & Libraries Used

- Python: For data analysis and visualization
- Pandas: Data manipulation and cleaning
- Matplotlib & Seaborn: Data visualization
- SciPy: Statistical analysis (t-test)
- Jupyter Notebook: Environment for developing the analysis
