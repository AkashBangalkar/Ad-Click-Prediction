# Ad Click Prediction

**Motivation**

The main motivation behind the project is “Targeted Advertising”. At its most basic, targeted advertising can just mean that ads are chosen for their relevance to site content, in the assumption that they will then be relevant to the site audience as well. Online advertisers can use different methods to target a particular advertisement on the user based on its traits. Most of company do this as part of social media like Facebook, LinkedIn etc. But most of the times the process goes wrong and the advertisement does not reach its target audience because it is sent out without actually understanding the probability of the occurring click.

**Problem Statement**
- In this article, we will work with the advertising data of a marketing agency to develop a machine learning algorithm that predicts if a particular user will click on an advertisement. The data consists of 10 variables: 'Daily Time Spent on Site', 'Age', 'Area Income', 'Daily Internet Usage', 'Ad Topic Line', 'City', 'Male', 'Country', Timestamp' and 'Clicked on Ad'.

- The main variable we are interested in is 'Clicked on Ad'. This variable can have two possible outcomes: 0 and 1 where 0 refers to the case where a user didn't click the advertisement, while 1 refers to the scenario where a user clicks the advertisement.

- We will see if we can use the other 9 variables to accurately predict the value 'Clicked on Ad' variable. We will also perform some exploratory data analysis to see how 'Daily Time Spent on Site' in combination with 'Ad Topic Line' affects the user's decision to click on the add.

The goal is to predict if a user would click on an advertisement based on the features of the user. Few assumptions made as a part of this project is:

1. User taken into consideration are between the age group of 19 to 61.
2. There is almost equal ratio of male and female internet users.
3. The ad topic is limited to what is given in the dataset.

**Data Set**

The dataset consists of below features:

- Daily Time Spent on Site: Consumer time on site in minutes
- Age: Customer age in years
- Area Income: Average Income of geographical area of consumer
- Daily Internet Usage: Average minutes a day consumer is on the Internet
- Ad Topic Line: Headline of the advertisement
- City: City of consumer
- Male: Whether or not consumer was male ~ 0 - Female / 1 - Male
- Country: Country of consumer
- Timestamp: Data and time
- Clicked on Ad: 0 - Not clicked on Ad / 1 - Clicked on Ad

*Checking Null Values*

### Exploratory Data Analysis

