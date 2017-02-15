# GA-projects
Data science projects in Python

In this repo, I have some of the projects I worked on from the GA data science course. I do all these projects in Python 2.7 using Jupyter Notebooks and some of them include visualizations from Tableau. The five projects in this repo are:

### 1. Analyzing SAT scores
This is a fairly basic project where I read in the average Reading, Verbal and Math SAT scores by state, apply summary statistics and make visualizations with matplotlib, seaborn and Tableau.

### 2. Analyzing Liquor Sales in Iowa
In this project, I read in sales data from a random sample of 10% of all liquor stores in Iowa. The rows in the dataframe contain transactions for stores that have a class E liquor license and some of the variables include city, county, bottle sold, volume sold, and store number for all of 2015 and the first quarter of 2016. The goal is to run a regression analysis to predict the total revenue for the rest of 2016 and advise the Iowa legislature on changing the liquor tax rates.

### 3. Analyzing Data Science Salaries from Indeed.com
In this project, I build a webscraper to scrape Indeed.com for Data Scientist salaries across the country. I then find the median salary (of the scraped listings the had salaries provided) and try to predict which of the remaining scraped listings will pay above the median and which of them will pay below and find which skills and key words hold the greatest predictive value.

### 4. West Nile Virus Prediction (Kaggle)
This is a project from Kaggle where I take in weather, mosquito trap location, testing data (whether or not a trap contained mosquitoes that tested positive for West Nile) and spraying data (where the city sprayed airborne pesticides to control adult mosquito population in the past) and build a model to predict when and where different species of mosquitoes will test positive for West Nile Virus in an attempt to help Chicago allocate resources more efficiently and effectively to prevent transmission of the disease.

### 5. Analyzing Terrorist Attacks from the Global Terrorism Database
The Global Terrorism Databse is an open-source database that includes information on terrorist attacks around the world from 1970 to 2015. It includes over 150,000 cases and tracks a lot of information including the target, how many people were injured or killed, and the perpetrator who claimed the attack. I have 3 goals for this project: 1. I try to get a better understanding of the different attacks and their distribution across the world. 2. I use Bayesian inference to compare terrorist attacks in the US before 9/11 and after 9/11 and see how they differ. 3. Since the year 1993 is missing from the dataset, I try to impute the number of bombings that occurred in 1993.

### 6. Predicting Cancer Relapse from Gene Expression Data (Capstone Project)
For my final project, I look at gene expression data from 424 ER+ breast cancer patients in remission and try to predict, solely using the patients’ gene expression levels, who will relapse and who will not. I use 2 standard machine learning classifiers, a Random Forest and a Gradient-Boosted Tree, but I also build another classifier from scratch called the Top Scoring Pairs algorithm which I describe in more detail in the project.