

# Data Portfolio: Kaggle to pivot chart in Excel.

# Table of contents 

- [Objective](#objective)
- [Data Source](#data-source)
- [Stages](#stages)
- [Design](#design)
  - [Mockup](#mockup)
  - [Tools](#tools)
- [Development](#development)
  - [Pseudocode](#pseudocode)
  - [Data Exploration](#data-exploration)
  - [Data Cleaning](#data-cleaning)
  - [Transform the Data](#transform-the-data)
  - [Create the SQL View](#create-the-sql-view)
- [Testing](#testing)
  - [Data Quality Tests](#data-quality-tests)
- [Visualization](#visualization)
  - [Results](#results)
  - [DAX Measures](#dax-measures)
- [Analysis](#analysis)
  - [Findings](#findings)
  - [Validation](#validation)
  - [Discovery](#discovery)
- [Recommendations](#recommendations)
  - [Potential ROI](#potential-roi)
  - [Potential Courses of Actions](#potential-courses-of-actions)
- [Conclusion](#conclusion)

# Objective 

- What is the key pain point? 

The Head of Marketing wants to find out the under represented demographic groups to determine where marketing campaigns should be improved.


- What is the ideal solution? 

To create a pivot chart that indicates the least sales. The chart should present the following information: 
- the age group
- the country 
- the gender
  

This will help the marketing team make informed decisions about where marketing improvements should be made.

# User story 

As the Head of Marketing, I want to use a pivot table that analyses sales for our bicycle company.

This dashboard should allow me to identify the the age group and country with the least sales.

With this information, I can make more informed decisions about where to improve sales.


# Data source 

- What data is needed to achieve our objective?

We need data on the company's sales for the past 5 years, to see how sales have been going. The data should include the following:
- sales made
- country
- age group
- gender



- Where is the data coming from? 
The data is sourced from the company's database(an Excel extract), [see here to find it.](https://www.kaggle.com/datasets/bhavyadhingra00020/top-100-social-media-influencers-2024-countrywise?resource=download)

# Stages

- Design
- Developement
- Testing
- Analysis
  
 # Design
## Pivot chart components required 
- What should the pivot chart contain based on the requirements provided?

To understand what it should contain, we need to figure out what questions we need the dashboard to answer:

1. Which areas have the least amount of sales?
2. Which age group buys the product the most?
3. Which gender uses the product the least?
4. Where can we implement new marketing strategies?



## Pivot chart

- What should it look like? 

Some of the data visuals that may be appropriate in answering our questions include:

1. Bar charts
2. Pie charts
4. Horizontal bar chart 




![Dashboard-Mockup](assets/images/dashboard_mockup.png)

