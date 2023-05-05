# Project: Writing a Data Scientist Blog Post!

## Introduce about project

    In this project, I use dataset [Stack Overflow Data - 2017 Survey](https://www.kaggle.com/datasets/stackoverflow/so-survey-2017) to answer the following questions:
#### Question 1: What is the distribution and scale of the data? For example, Do respondents like programming, what country do they live in, do they go to university, what industry do they work in and what programming language do they use to work? What programming language?

#### Question 2: How are their salaries? does it depend on whether they love programming, or does it depend on the programming language, the country they are working in, and the industry they work in?

#### Question 3: How satisfied is their job with the work they are doing? What is the correlation between satisfaction and salary they receive?

## Practice

### Library

    In this project, we using some popular libraries to explore data and find answers for above questions:
    1. NumPy: NumPy is a library for working with arrays and matrices of numerical data. It provides fast mathematical operations and supports a wide range of mathematical functions.
    2. Pandas: Pandas is a library for data manipulation and analysis. It provides data structures for working with tabular data, as well as tools for cleaning and transforming data.
    3. Matplotlib: Matplotlib is a plotting library that allows you to create a wide range of visualizations, including line plots, scatter plots, histograms, and more.
    4. Seaborn: Seaborn is a higher-level visualization library that builds on top of Matplotlib. It provides a simpler interface for creating complex visualizations, such as heatmaps and violin plots.
    
### Motivation

    To understand what factors affect an individual's salary, so that I myself can hone more skills to increase my self-worth.
    
### File in repository

    survey_results_public.csv: contain data of survey
    Project 1.ipynb: all analyst 
    README.md: all guide and introduce about project

### Result

#### Question 1:

    We can see in survey, data was distributed as below:
    - The majority of people surveyed are living and working in the US and Europe.
    - Most of the respondents have a hobby of programming, working full time, gender is male. The special thing is that a large number of them do not go to university.
    - The most used languages are JavaScript, SQL Java, PHP, Python.
    - The most chosen IT majors are Web developer, Desktop Application Developer, Mobile Developer.
    
#### Question 2:

    - As we can see that the salary of programmers is positively correlated with the number of years of experience, the average salary of programmers increases as the number of years of experience increases. Salary is also proportional to the size of the company they are working for.
    - In addition, the salary depends on the country they are working in, the programming language they use, the IT industry they are working in or whether they work full time or part time. Especially when it comes to college graduates, those who don't have a higher average salary.
#### Question 3: 

    From the results of the analysis, we can see that the correlation of salary with job satisfaction is not close. There are many people whose salary is not high but still have a high level of job satisfaction, but there are also many people who have high salary but are not satisfied with the job. We can also see that the correlation coefficient between the two indexes is 0.116, which indicates that they have a low correlation.