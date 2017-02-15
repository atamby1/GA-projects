Project 3: Web Scraping & Classification

### Description

For this project, I’m working as a data scientist for a contracting firm that's rapidly expanding. Now, they need to leverage data to win more contracts. My firm offers technology and scientific solutions and wants to be competitive in the hiring market. My principal thinks the best way to gauge salary amounts is to take a look at what industry factors influence the pay scale for these professionals.

Aggregators like [Indeed.com](https://www.indeed.com) regularly pool job postings from a variety of markets and industries. My job is to understand what factors most directly impact data science salaries and effectively, accurately find appropriate data science related jobs in your metro region.

#### Project Summary

In this project, I practice two major skills. Collecting data by scraping a website and then building a binary predictor.

I am going to collect salary information on data science jobs in a variety of markets. Then using the location, title, and summary of the job, I will attempt to predict a corresponding salary for that job. While most listings *DO NOT* come with salary information (as you will see in this exercise), being to able extrapolate or predict the expected salaries for other listings will be extremely useful for negotiations.

Normally we could use regression for this task; however, instead we will convert this into a classification problem.

The first part of assignment will be focused on scraping [Indeed.com](www.indeed.com) and the second will be focused on using the listings with salary information to build a model and predict salaries.