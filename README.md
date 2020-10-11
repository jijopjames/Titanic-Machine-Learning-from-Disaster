# Titanic-Machine-Learning-from-Disaster

## [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic) 

This model is based on Logistic Regression.

1. The data used to determine my outcome is avalable on the data folder or can be found from the competition page. 
2. Data folder contains:
    - gender_submission.csv - A sample formate for output submission
    - test.csv - Test dataset
    - train.csv - Train dataset
3. titanic_survival.ipynb contains the code for data preprocessing and modeling.
4. submission.csv is the outcome of the data modeling.

### Data Discription

| Variable  |Definition | Key |
| ----------- | ----------- | ----------- |
| survival | Survival | 0 = No, 1 = Yes |
| pclass | Ticket class | 1 = 1st, 2 = 2nd, 3 = 3rd |
| sex | Sex | |
| Age | Age in years	| |
| sibsp |	# of siblings / spouses aboard the Titanic | |
| parch	| # of parents / children aboard the Titanic | |
| ticket | Ticket number | |
| fare | Passenger fare | |
| cabin | Cabin number | |
| embarked | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton |

#### Variable Notes

pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.



