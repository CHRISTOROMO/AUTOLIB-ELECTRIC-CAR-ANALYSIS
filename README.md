# AUTOLIB-ELECTRIC-CAR-DATA-REPORT
 
Business Understanding 
 
Business Overview
Autolib is a company that specializes in electric car rental services to its customers. Their operations entailed a scenario that a customer picks an electric car from a charging station and commutes with it to their destination, thereafter the customer parks the car in a charging station where the next customer can pick and use it.
 
Business Objective
The business wants  to understand electric car usage over time and get insights on the most popular hour of the day for picking up a shared electric car.
 
Business Success Criteria
Identifying  the most popular hour of the day for picking up a shared electric car (Bluecar) in the city of Paris over the month of April 2018.
 
Assessing the Situation
Resource Inventory
 Dataset
     i). Autolib Dataset: (Links to an external site.)
     ii).Dalberg documentation about Autolib: (Links to an external site.)
. 
Software(Github, Python, Vs Code, Jira)
				
 
Assumptions
	The data is correct and very few errors
 
 
Constraints
There are no constraints
 
Data Mining Goals
Our data mining goals for this project are as follows:
Identifying the most popular hour of the day for picking up a shared electric car (Bluecar) in the city of Paris over the month of April 2018.
Identifying the most popular hour for returning cars?
Identifying the most popular station overall and at the most popular picking hour.
Identifying the postal code that is most popular for picking up Blue cars and if the station belongs to that postal code overall and at the most popular picking hour.
Identifying if the results change if we consider Utilib and Utilib 1.4 instead of Blue cars.
Data Mining Success Criteria
Our success criteria will be measured by the following criteria:
We target to get the best time and the total number for picking up a shared electric car(Bluecar) from the month of April 2018.
 
Producing a Project Plan 
The project plan will basically use the Kanban framework. We shall use the Jira platform to display the board. The link to Jira is link
 
 
 
 
 
Data Understanding 
 
Data Understanding Overview
For this project, we are using the availed dataset by the company. The dataset is
Autolib Dataset
 
Data Description
We have one dataset available for this project. A detailed description of the datasets is 
provided as follows:
Autolib Dataset:- The dataset for this project contains 25 columns. These columns outline various metadata about the Autolib companies. The columns also contain two datatypes i.e object and float.
 
 
 
 
Verifying Data Quality
None of the two datasets had any missing values. There were also no known data errors in the datasets.
 
 
Data Preparation 
These are the steps followed in preparing the data 
i). Loading Data
    Loaded the datasets from the CSV using the Python Pandas
ii). Cleaning Data
    While doing data exploration on the dataset, we noted null values at the ‘Displayed comment’ and ‘Scheduled at’ columns. Since the columns were not relevant to the analysis, we dropped them.
 
Analysis 
The basic analysis done was the predictive analysis of checking the Bluecar, Utilib and	Utilib 1.4 counters respectively.

 
The above analysis was done using Python language with the help of Virtual studio Code. The full and detailed analysis can be found in the following Github repository link
 
 
Recommendation 
 
From our full analysis, we would recommend more Bluecar cars to be allocated for 2100 hours in order to capitalize on the abundance of the clients at the hour. This will therefore boost the revenue of the company.
We also recommend adding more Bluecar cars at Postal Code 75015 since it is the most popular location for picking the cars. This will increase the number of the cars being picked by clients hence more revenue.
