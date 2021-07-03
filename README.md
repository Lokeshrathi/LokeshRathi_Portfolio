# Welcome to My Portfolio

I have listed down some Data Science related projects here!

# **Project 1-** _LinkedIn-Profile-Scraping_ ([Link](https://github.com/Lokeshrathi/LinkedIn-Profile-Scraping))
Scraping LinkedIn Data of Top 10 Data Analyst in Bangalore via Google Search

In this Project, I have Scraped LinkedIn Data of Top 10 Analyst in Bangalore, India.

```
Scraping Overview:
1. Used Google Search to find the Profiles of Top 10 Analyst - (*'site:linkedin.com/in/ AND "Data Analyst" AND "Bangalore"'*)
2. Extarcting all the LinkedIn Profile Links from the Page.
3. Individually visiting each profile and extacting data.
**a) Name
b) Title
c) Company
d) Education
e) Followers
f) URL**
```
## Result

![Image](https://github.com/Lokeshrathi/LinkedIn-Profile-Scraping/blob/main/LinkedIn%20Profiles.PNG)

# **Project 2-** _Instagram_Bot_
This BOT signs into your Instagram Account and Likes and Comments on Posts with specific tags.

## Inspiration:
Living in the world of Automation, we are surrounded by technology all around us, Creating and Building is the only way to keep oneself updated and learning all the way.
Also, I would appreciate any Pull Requests/Issues one may encounter.
```
Steps to follow:
1. Make sure to download your WebDriver(Chrome/Firefox) [Link](https://chromedriver.chromium.org/downloads) 
2. Enter your Details like Username, Password, Hashtags and Comments in the details.py file
3. Run the code for the first 20-30 links, running any further Instagram might stop your program from adding Comments further.
```
## Results!

![Image](https://github.com/Lokeshrathi/Instagram_bot/blob/main/Instagram%20Results.jpeg)


# **Project 3-** _Covid-Vaccination-Slot-check_ ([Link](https://github.com/Lokeshrathi/Covid-Vaccination-Slot-check))

Want to know your Covid nearest vaccination center and slots availability?
```
Input: 
1. Enter your Postal Code.

2. Enter for Number of days you want to see the results for.

3. Enter the Start date.

## Source: https://www.cowin.gov.in/home
## Also you can send this as a mail if someone might require the data!
```

# **Project 4-** _Manipulating-Mail-Account_ ([Link](https://github.com/Lokeshrathi/Manipulating-Mail-Account))

Have you ever wanted to delete emails in your mail box but you know it will take a lot of your time and effort to do it manually ?
```
#### Things you can do:
1. Delete Mails from a Specific Sender
2. Delete Mails for a particular Time Periods.
3. Delete Mails having a Particular Subject!

- Lets see How Python comes to our rescue!

We gonna be using the Python built-in's imaplib module, but if you want to use some sort of API, we have a tutorial on how to use Gmail API where we show how to read, send and delete emails in Python. 

- To generate App Password
- https://support.google.com/accounts/answer/185833
```

-
# **Project 5-** _IBM-HR-Attrition-Analysis-and-Prediction_ ([Link](https://github.com/Lokeshrathi/IBM-HR-Attrition-Analysis-and-Prediction))

- In this Notebook, we try to analyse and predict on *Attriction* on the IBM employee Dataset. 
- Dataset has 1470 rows and 35 columns.

```
Data Cleaning:

 - Here we remove:
  1. Redundant values
  2. Values with high collinearity.
  3. Removing columns having more than 96% similar values.
  4. Columns that have least correlation with the *target columns*.
 - Data was reshaped to 1340 rows and 35 columns.

## Data Scaling:
  - *RobustScaler* is a transformation technique that removes the median and scales the data according to the quantile range (defaults to IQR: Interquartile Range). The IQR is the range between the 1st quartile (25th quantile) and the 3rd quartile (75th quantile). It is also robust to outliers, which makes it ideal for data where there are too many outliers that will drastically reduce the number of training data.
  
## Data Modeling:
  - We use **XGBoostClassifier** to model our data with hyper-parameter tuning.
  - Model gets us an **accuracy score of 87.30% and log_loss of 4.38.**
  ```
  
 # **Project 6-** _Indian-Elections-2019-Analysis_ ([Link](https://github.com/Lokeshrathi/Indian-Elections-2019-Analysis))
 ```
- This Notebook gives you a deatiled analysis on **INDIAN ELECTION 2019**. 
- Data has been pulled from [kaggle](https://www.kaggle.com/lokeshrth4617/indian-election-2019?scriptVersionId=37582691)
- Tech used - **Python 3.0,Jupyer-Notbook,Plotly, Seaborn**
```


