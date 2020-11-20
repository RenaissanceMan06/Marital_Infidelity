# Marital Infidelity
 
![Image](infidelity_project.png)

The aim of my project is to determine the predictors of marital infidelity. Couples therapists view extramarital affairs as one of the most damaging relationship events and 
one of the most difficult problems to treat in couples therapy. Furthermore, a review of 
ethnographic accounts of conjugal dissolution across 160 societies found that infidelity was the 
single most common cause of marital dissolution. Rather than seeking couple therapy when 
extramarital affairs happen, can we predict the factors of extramarital affairs? If so, we may help 
prevent marital affairs from happening. The aim of the current project is to determine the 
predictors of extramarital affairs. 


# Data Set
To tackle this project, I utilized Fair’s Affair data set. It 
featured 10 columns and 601 rows. Some notable features were frequency of affairs, gender, age, 
years married, and religiousness. After running a correlation matrix, the significant predictors 
for my model were years married, religiousness, and happiness rating. 

![image](Correlation.png)

# Marital Happiness and Infidelity

Happiness rating was categorized as 1 = very unhappy, 2 = somewhat 
unhappy, 3 = average, 4 = happier than average, and 5 = very happy. Looking at the bar plot, 
most affairs occurred with respondents whom answered in the 1 and 2 categories. The least 
affairs occurred with respondents in the 5 category. The mean for happiness rating was *M* = 3.93 
and a *SD* = 1.10.

![image](happy_rating_affairs.png)

# Affair by Sex

Affair by sex did not appear to be statistically significant between the sexes. Males had a 
mean of *M* = 1.50 affairs in the past year with a *SD* = 3.29. Females had a mean of *M* = 1.42 
affairs in the past year with a *SD* = 3.31. 

![image](affairs_sex.png)

# Affair Frequency by Sex

How often did the sexes engage in extramarital affairs during the past year varied 
between categories. However, overall, both sexes appeared to engage in extramarital affairs just about 
equally. 

![image](male_female_frequency.png)
Both in training and 
testing, the model did perform well with some of the predictors chosen from the correlation matrix. 


# GitHub Repository
[Link](https://github.com/RenaissanceMan06/Marital_Infidelity)
