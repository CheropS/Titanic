# Titanic 

## Project Description 
This project looks into analyzing data from the passengers from the Titanic and understanding the ones who survived and the ones who did not. 
- The main aim is to investigate the survivors and those who lost their lives when the ship sank. 

### Understanding the Variables
1. survival	Survival	0 = No, 1 = Yes
2. pclass	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd
3. sex	Sex	
4. Age	Age in years	
5. sibsp	# of siblings / spouses aboard the Titanic	
6. parch	# of parents / children aboard the Titanic	
7. ticket	Ticket number	
8. fare	Passenger fare	
9. cabin	Cabin number	
10. embarked	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton

#### Notes on the variables 
- pclass: A proxy for socio-economic status (SES)
- 1st = Upper
- 2nd = Middle
- 3rd = Lower
- age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5
- sibsp: The dataset defines family relations in this way...
- Sibling = brother, sister, stepbrother, stepsister
- Spouse = husband, wife (mistresses and fiancés were ignored)
- parch: The dataset defines family relations in this way...
- -- Parent = mother, father
- -- Child = daughter, son, stepdaughter, stepson
- -- Some children travelled only with a nanny, therefore parch=0 for them.

## Files in the Project 
The project has 3 files which contain the following:
* [Training set](/titanic/train.csv): This contains the primary csv file that we will use in this project to train the dataset, 
* [Validation](/titanic/test.csv)
* [Gender](/titanic/gender_submission.csv)

