# Sales-Analysis-Using-Python-to-Answer-Business-Questions

PROBLEM STATEMENT: Keith Electronics is a newly started electronic products company which sells products such as phones, laptops, headphones chargers, batteries, etc. The company just completed its first financial year in the market and is now looking to increase its presence all over the United States. As the lead Data Analyst at keith Electronics you are tasked with analyzing the past 12 months of sales data available with you to derive insights and answer the following business questions:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What product sold the most? Why do you think it sold the most?
- What products are most often sold together?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?

Insights from your analysis will be used to drive business strategy and make important data-driven business decisions. You must be able to back your insights using data and give a detailed explanation of your findings.

You're given a CSV file containing 12 months worth of verified sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc. 


In this project we use Python Pandas, Numpy, Matplotlib and Seaborn to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc. 

Detailed Project Description (Step-by-Step)

We start by cleaning our data. Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 5 high level business questions related to our data:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What product sold the most? Why do you think it sold the most?
- What products are most often sold together?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?

To answer these questions we walk through many different pandas, Seaborn & matplotlib methods. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs

After all the analysis has been done(required graphs have been plotted & insights have been derived), we can create a dashbord to display all our plots and insights which can then be presented to the management for further action.
