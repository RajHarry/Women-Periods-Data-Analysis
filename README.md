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

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

×
Drag and Drop
The image will be downloaded
