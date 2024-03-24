# Employee Attrition

## Business Case : 
Attrition is the silent killer that can switly disable even the most successful and stable of the organizations in a shockingly spare amount of time.
Hiring new employees are extremely complex task that requires capital, time and skills.Also new employee costs a lot more than that Persons salary.

- The cost of hiring an employee goes far beyond just paying for their salary to encompass recruiting, training, benefits, and more.
- Small companies spent, on average, more than $1,500 on training, per employee, in 2019.
- Integrating a new employee into the organization can also require time and expenditures.
- It can take up to six months or more for a company to break even on its investment in a new hire.

## Dataset
Dataset Link - [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)


## Algorithm 
In this project, I have developed a Machine Learning Model to predict the Employee Attrition by implementing various Machine Learning Algorithms.
Conducted exploratory data analysis using various data visualization techniques.

Results from different algorithims : 
![Example Image](example.png)

Since accuracy won't be a good measure, looked at alternate metrics like ROC-AUC and recall to determine the best algorithm.

Achieved best results with randomforest.
Additionaly feature importance is also taken out from random forest model.

## Deployment

Made a WEB API using [Flask](https://flask.palletsprojects.com/en/) framework and deployed it on [Heroku](https://www.heroku.com/) cloud platform.
