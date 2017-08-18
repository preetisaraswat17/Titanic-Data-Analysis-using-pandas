# Titanic-Data-Analysis-using-pandas
Analysis of Titanic dataset(kaggle) using python

1)	Download Titanic data from kaggle ( https://www.kaggle.com/c/titanic/data). Analyze the data and its columns
We have following Variable in that data:
survival-(0 = No, 1 = Yes)
pclass-(Ticket class=>1 = 1st, 2 = 2nd, 3 = 3rd)
sex-(male/female)	
Age-(Age in years)
sibsp	Number of siblings / spouses aboard the Titanic	
parch	Number of parents / children aboard the Titanic	
ticket(Ticket number)
fare(Passenger far)
cabin(Cabin number)	
embarked(Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton)

2) When we analyze the survivors data, we see that not every class is evenly distributed. 
A look over each column tells us that there are a few columns that need to be further analyzed, for example:
      a)	Survival count of females as compared to men
      b)	Age and class are also not distributed evenly, it looks there are more survivors in certain class and age range
      c)	Embarked-there seems to be certain pattern in port of embarkation also for higher survival rate.

3)	Before analysing these columns we need to make sure data is tidy.Try to find if there is any missing data
    There are total 891 values. Some columns have missing values 
        Age            714 non-null float64
        Cabin          204 non-null object
        Embarked       889 non-null object

4)	We Remove these missing values by backward fill and forward fill
5)	See if there is any duplicate data for any passenger(there was no duplicate data so we don’t need to remove them) 
6)	Now we can further analyze the columns as per survival count.
7)	I have explained all steps in code with comments and graphs. The plots are also uploaded separately.
