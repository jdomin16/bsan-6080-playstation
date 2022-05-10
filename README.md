
# Playstation Audience Analytics Team Project
![alt text](https://github.com/LMU-MSBA/bsan-6080-playstation/blob/main/playstation-logo.png) 

# Table of Contents
* [Sprint 1: ](https://github.com/LMU-MSBA/bsan-6080-playstation/blob/main/README.md#sprint-1)
* [1. Business Understanding Phase](https://github.com/LMU-MSBA/bsan-6080-playstation/blob/main/README.md#business-understanding-phase)
	* [1.1 Determine Business Objective](https://github.com/LMU-MSBA/bsan-6080-playstation/blob/main/README.md#11-business-objectives)
	* [1.2 Assess Situation](https://github.com/LMU-MSBA/bsan-6080-playstation/blob/main/README.md#12-assess-situation)
	* [1.3 Determine Data Mining Goals](https://github.com/LMU-MSBA/bsan-6080-playstation/blob/main/README.md#13-determine-data-mining-goals)
	* [1.4 Produce Project Plan](https://github.com/LMU-MSBA/bsan-6080-playstation/blob/main/README.md#14-produce-project-plan)
* [Sprint 2: ](https://github.com/LMU-MSBA/bsan-6080-playstation/blob/main/README.md#sprint-2)
* [Sprint 3: ](https://github.com/LMU-MSBA/bsan-6080-playstation/blob/main/README.md#sprint-3)
* [3. Data Preparation Phase](https://github.com/LMU-MSBA/bsan-6080-playstation/blob/main/README.md#data-preparation-phase)
	* [3.1 Select Data](https://github.com/LMU-MSBA/bsan-6080-playstation/blob/main/README.md#31-select-data)
	* [3.2 Clean Data](https://github.com/LMU-MSBA/bsan-6080-playstation/blob/main/README.md#32-clean-data)
	* [3.3 Construct Data](https://github.com/LMU-MSBA/bsan-6080-playstation/blob/main/README.md#33-feature-selection)

# Sprint 1: 
# Business Understanding Phase
## 1.1 Business Objectives:
Playstation is looking for a an analyst as a part of their Audience team. This position is pivotal as this will entail a vital role in shaping 
communication with consumers. Playstation wants to initiate a global marketing strategy to reach all of its customers. The objectives 
include figuring out how best to reach customers, how to drive up engagement, promote subscription growth of its popular Playstation Plus online service.
Success will be measured through how well we meaure up when compared to our key performance indicators and how well we can implement and deploy our project plan. 

## 1.2 Assess Situation
Understand the current main revenue sources and main products of playstation. Including video game consoles, media center's usage and user reviews. 
What efforts and improvements have PlayStation made to maintain and develop these products. Learn the company's development strategy and marketing strategy. 
For example, using different subscription models to attract customers to comsume. The last is  research the risks the company faces. 
These risks come from both internal and external sources. Employees are not satisfied with the company's treatment. And there are strong competitors outside.

### Terminology

Text mining: is the process of transforming unstructured text into a structured format to identify meaningful patterns and new insights.

Sentiment Analysis: is contextual mining of text which identifies and extracts subjective information in source material, and helps a business to 
understand the social sentiment of their brand, product or service while monitoring online conversations.

Customer segmentation: is the process of dividing customers into groups based on common characteristics so companies can market to each group effectively 
and appropriately.

Customer targeting: is the act of reaching out to a portion of your customer list to re-engage them and drive sales.

API: stands for application programming interface, which is a set of definitions and protocols for building and integrating application software.

Costs and Benefits

Some of the costs would be the data as it can be very expensive and have a very large volume. Meaning it would be expensive or hard to store. 
Time is another big factor, as this time could also be used on other things such as on how PlayStation could stand out more from competitors, like Xbox. 
Manpower would be limited, as many employees from different departments would have to focus on this project instead of working on other important projects.

On the other hand, from this project PlayStation could obtain numerous benefits. First of all, increased customer satisfaction. 
This would be obtained by listening more carefully to our customers and through our sentiment analysis that would search for very useful feedback to 
improve the relationship with customers. Subscriptions for services would also most likely increase as PlayStation would be targeting and segmenting 
their customers more efficiently. Lastly and most importantly, sales and revenue would increase. This is due to PlayStation trying to prioritize their customers, 
being able to reach their correct audience effectively and improving their services.


## 1.3 Determine Data Mining Goals
We are going to use web scraping and calling an API that we learned in the class to find the information we need for the text mining goals part. 
From the information we get, we will figure out at least two data mining goals for the PlayStation and find out which are the prioritize goals 
and reasons behind it. At last, we will determine what are the Success Criteria of the data mining for PlayStation from the information found online 
and understand why.

## 1.4 Produce Project Plan
We will be gathering data for this project by using APIs, web scraping and finding prepared datasets on the internet.

A quick rundown of each phase of the project plan is given below:

1. DATA UNDERSTANDING

* Tools Used: Web browser to scan for useful data, discussions to set performance metrics and KPIs

* Resources: Domain Knowledge, Project Understanding

* Inputs: Collective knowledge

* Outputs: A clear understanding of the data to be used and how to use it

* Dependencies: Time availability, ability to find the appropriate datasets, data access

* Duration: 2-3 days

2. DATA PREPARATION

* Tools Used: Postman for APIs, Python for Web Scraping, SQL and Python for Data Cleaning (ETL)

* Resources: Access to Software, datasets,

* Inputs: Datasets from the sources

* Outputs: Clean dataset for modeling

* Dependencies: Ability to completely clean datasets, combine them and utilize all the features, quality of data

* Duration: 5-7 days

3. MODELING

* Tools Used: Python to create models, Tableau to visualize models better

* Resources: Access to clean datasets

* Inputs: Cleaned datasets

* Outputs: predictive models to determine potential growth

* Dependencies: Domain knowledge of models to run

* Duration: 4-6 days

4. EVALUATION

* Tools Used: Python to perform evaluation using performance metrics

* Resources: Access to software, Domain Knowledge

* Inputs: Models created to understand customer data

* Outputs: Understanding of models and finding the right model and strategy

* Dependencies: Evaluation criteria, ceilings

* Duration: 3-7 days

5. DEPLOYMENT

* Tools Used: Slides, Docs to create a presentable version and a detailed version of the results

* Resources: Team discussions

* Inputs: Post evaluation insights, analysis

* Outputs: Project presentation, report, and deployment

* Dependencies: Time availability, Project success criteria met

* Duration: 2-5 days

# Sprint 2: 

# Sprint 3: 
# Data Preparation Phase
## 3.1 Select Data & Clean Data
In data preparation, we needed to import pandas firstly.Then, we used pd.read_csv() function to read csv file ’Sony_Playstation_tweets.csv’. After loading the data set, we need a descriptive analysis of data. We use following function for analysis:
1.Head(): get the first 5 rows
2.Describe(): calculating some statistical data like percentile, mean and std of the numerical values of the Series or DataFrame
3.Info(): prints information about the DataFrame
4.Isnull().sum(): total number of null
5.Size: find dataframe size
6.Shape: find dataframe shape
7.Ndim: find the number of dimensions
So  we  observer  the  first  5  rows  of  dataframe.  And  understand  some  statistical  data  and  data  type  for  each  column. Size  is  699048.  Shape  is (19418,  36).  Dimension  is  2. In  the  missing  value  check,  we  found  that  some  columns  have  a  large  number  of  missing  values.  For example, ‘place’ has 19417 missing value. We decide to dropthese  columns.To  delete  these  columns,  we  use  drop()  function. We  keep these columns:(id,  date,  username,  tweet,  language,  replies_count,  retweets_count,  likes_count,  hashtags).At  last,  we  use  isnull().sum()  to  check  the  data  after  cleaning.  We  can  found  there  is  no  missing  value  on  the  dataset. Data  preprocessing  is  complete,  wecan  proceed  to  the  next  step.
## 3.2 Feature Selection
Machine learning models allow businesses to predict consumer buying habits, market trends, popular products, and more, allowing retailers to make informed business decisions based on these predictions. Additionally, companies can build models to analyze larger, more complex data and deliver faster, more accurate results. It enables organizations to identify lucrative opportunities and potential risks faster. Organizations gain a more accurate and robust ability to forecast demand. It can also help companies take advantage of important opportunities to gain deeper insights into data. For the feature selection we didn't have enough information to go with, so we had to create another variable which was Region where we wanted tosee whether being in the US compared to the rest of the world, it had an impact on the subscription status. Along with Region, we used the Pay Cycle and System variables to figure out which of our subscribers we could predict to stay with us.

