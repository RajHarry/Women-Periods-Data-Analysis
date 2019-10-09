# Find Next Period Time Based on Previous Periods Dates

This is a full analysis and predicting the next approximate period dates for an woman based on her previous period dates.

## Getting Started

## Regarding the data:

1.	The data is taken from a subset of real users who were using an iOS app to record their feminine health data, for real.
### 2.	User.csv
```
a.	Personally identifiable information has already been removed
b.	The column named “dob” refers to a user’s birthday, and empty values mean that the user did not provide their birthday to the app
c.	The column named “cycle_length_initial” refers to the value (in days) that a user provides to the app during their onboarding to indicate how many days they think their menstrual cycle is 
d.	The column named “period_length_initial” refers to the value (in days) that a user provides to the app during their onboarding to indicate how many days they think their periods last for
e.	The column named “id” is the User ID and can be used as a foreign key to link a given user to data rows with the same “user_id” in Period.csv and Symptom.csv data tables
```
### 3.	Symptom.csv
```
a.	Each symptom has a default & minimum value of 0, and a maximum value of 100, with 100 being the most severe
```
### 4.	Period.csv
```
a.	The column named “start_date” refers to the first day of bleeding of a period
b.	The column named “end_date” refers to the last day of bleeding of a period
```
### 5.	Period trivia
```
a.	Example of “What is period length?”
  ■	1st Jan 2019: 1st day of bleeding (a.k.a period start date)
  ■	5th Jan 2019: Last day of bleeding (a.k.a period end date)
  ■	Period Length = 5 days
b.	Example of “What is cycle length?”
  ■	 1st Jan 2019: 1st day of bleeding (a.k.a period start date)
  ■	1st Feb 2019: 1st day of bleeding (a.k.a next period start date)
  ■	Cycle Length = 31 days
```

