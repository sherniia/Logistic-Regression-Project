# Logistic-Regression-Project
Logistic Regression project with fake advertisement dataset

This is one of the projects given in the Udemy course'Python for Data Science and Machine Learning' by Pierian Data. In this project I worked with a fake advertising data set, indicating whether or not a particular internet user clicked on an Advertisement. Using logistic regression model I created a model that predicts whether an internet user has clicked on an Advertisement or not. 

Techniques used in this project: 
 - data cleaning 
 - data visualization
 - machine learning


As always, one starts by exploring the dataset. I knew from the start that my response variable is whether the user clicked on advertisiment or didn't. Since my response variable is binary, it makes sense to use Logistic Regression. 

This data set contains the following features:

* 'Daily Time Spent on Site': consumer time on site in minutes
* 'Age': cutomer age in years
* 'Area Income': Avg. Income of geographical area of consumer
* 'Daily Internet Usage': Avg. minutes a day consumer is on the internet
* 'Ad Topic Line': Headline of the advertisement
* 'City': City of consumer
* 'Male': Whether or not consumer was male
* 'Country': Country of consumer
* 'Timestamp': Time at which consumer clicked on Ad or closed window
* 'Clicked on Ad': 0 or 1 indicated clicking on Ad


Here are some exploratory plots:

![Plot 1](https://user-images.githubusercontent.com/94130159/167310695-352cf0b1-f8d8-4e92-ba47-e7a06af5e038.png)

![plot 2](https://user-images.githubusercontent.com/94130159/167310698-6b8aa9e4-156a-4697-8123-17d1bf23d890.png)

![plot3](https://user-images.githubusercontent.com/94130159/167310700-b7461e32-781c-4627-b3df-1e732c95a900.png)


After exploring the dataset, I decided to use 'Daily Time Spent on Site', 'Age', 'Area Income', 'Daily Internet Usage' as my explanatory variables.


Here's the screenshot of classification report for the model:

<img width="488" alt="Screen Shot 2022-05-08 at 1 35 30 PM" src="https://user-images.githubusercontent.com/94130159/167310769-44a6dba7-8e03-495e-ae79-e23ff705f0a9.png">

