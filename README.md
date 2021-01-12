### learn-nyc-parking-violations
## Learn Python Data Analytics By Example: NYC Parking Violations

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

### Introduction

While working towards my Master's in Business Analytics, I found that learning by example is the best way for me to learn Python data analytics.  Being given a dataset and a set of coding tasks is much more beneficial than reading a textbook or listening to a professor.  

I want to share this method of learning with others who will also benefit.  All you need is a Python development environment (I recommend [Jupyter Notebook](https://jupyter.org/)) and a willingness to learn and have fun.

Included in this article is a list of data analytics tasks, followed by a detailed walkthrough of how to complete the tasks.  Please try to complete the tasks yourself before reading through the walkthrough - you will get more out of it that way.  Do keep in mind that there are many many ways to solve coding problems, so your code likely will not match mine word for word.

### Project Description

For this project we will use a dataset of 50,000 parking violations issued in New York City during the 2021 fiscal year.  The dataset was created in January 2021 and contains data from April 1 to November 30, 2020 sourced from [NYC Open Data](https://data.cityofnewyork.us/City-Government/Parking-Violations-Issued-Fiscal-Year-2021/pvqr-7yc4).

You will need to install the [pandas](https://pandas.pydata.org/) and [matplotlib](https://matplotlib.org/) libraries, if you do not already have them.


### Data Analytics Tasks

Please perform the following tasks in Python using the *violations.csv* dataset available from the GitHub repo.
1. Read the CSV file containing the NYC parking violation data. Change the 'Issue Date' column to a date format. Then print out the number of rows imported.
2. Perform exploratory data analysis on the imported dataset to identify invalid data.  Write code to remove the impacted rows.  Then print out the number of rows remaining in the dataset.
3. Display a simple plot that shows the number of parking violations issued for each vehicle year.
4. List the top 5 violation codes for vehicles that are registered in states other than NY.
5. Name the street where Hondas received the most parking violations.
6. For vehicles that are from NY only, create a plot displaying the ratio of plate types that are not passenger, month by month.
7. Determine whether the color of vehicles with passenger plates receiving the most violations is the same as the color of vehicles with commercial plates receiving the most violations.
8. Display the number of registration states represented in the data and the average number of parking violations per registration state.
9. Display the plate type that has the most parking violations for each violation code.
10. Calculate the percentage of parking violations in each county and display in descending order.
