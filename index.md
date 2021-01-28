# Predictors of Marital Infidelity
 
![Image](infidelity_project.png)

Couples therapists view extramarital affairs as one of the most damaging relationship events and 
one of the most difficult problems to treat in couples therapy. A review of 
ethnographic accounts of conjugal dissolution across 160 societies found that infidelity was the 
single most common cause of marital dissolution (Whisman, Gordon, & Chatav, 2007). Rather than seeking couple therapy when 
extramarital affairs happen, can we predict the factors of extramarital affairs? If so, we may help 
prevent marital affairs from happening. The aim of the current case study is to determine the 
predictors of extramarital affairs. 


# Data Set
To tackle this case study, I utilized Fair’s Affair data set. It 
featured `10 columns and 601 rows`. Some notable features were frequency of affairs, gender, age, 
years married, and religiousness. After running a correlation matrix, the significant predictors 
for my model were years married, religiousness, and happiness rating. 

![image](Correlation.png)

# Marital Happiness and Affairs

Happiness rating was categorized as 1 = very unhappy, 2 = somewhat 
unhappy, 3 = average, 4 = happier than average, and 5 = very happy. Looking at the bar plot, 
most affairs occurred with respondents whom answered in the 1 and 2 categories. The least 
affairs occurred with respondents in the 5 category. The mean for happiness rating was *M* = 3.93 
and a *SD* = 1.10.

![image](happy_rating_affair.png)

# Affair by Sex

Affair by sex did not appear to be statistically significant between the sexes. Males had a 
mean of *M* = 1.50 affairs in the past year with a *SD* = 3.29. Females had a mean of *M* = 1.42 
affairs in the past year with a *SD* = 3.31. 

![image](affairs_sex.png)

# Affair Frequency by Sex

How often the sexes engage in extramarital affairs during the past year varied 
across categories. However, overall, both sexes appeared to engage in extramarital affairs just about 
equally. 

![image](male_female_frequencies.png)

# Training Regression Model

The predictors for my model were years married, 
religiousness, and happiness. My target variable was affairs. I used a split validation to partition 
the data set for my model. The training model utilized a data set with 417 instances while my test 
model used 178 instances. According to my model, the predictor for affairs is years married. It had a *p* value of *p* = 0.00. Surprisingly, happiness rating did not appear to have a 
statistically significant effect on my model. It had a *p* value of *p* = 0.95. The attribute 
religiousness did not appear to have a statistically significant effect neither. It had a *p* value of *p* 
= 0.75. 

![image](Training%20model.png)

# Test Model

In the testing model too, religiousness and happiness rating did not appear as significant 
predictors of infidelity. However, years of marriage did appear as a predictor. It had 
a *p* value of *p* = 0.00.  


![image](Appendix.png)

# Attribute of Prediction Model

Affairs start to happen six years into marriage. That is when a spouse has had one affair in the past year. Eight years into the marriage, a spouse has had three affairs in the past year. Approaching 10 years into the marriage, a spouse has had 4-10 affairs in the past year. A marriage past 10 years, a spouse has had either two affairs in the past year or once daily or weekly for the past year. 

![image](MODEL%20PREDICTION.png)

# Conclusion

Although the model predicted years of marriage as a significant predicted of marital infidelity, we must take into account the adjusted R-squared and Fair's dataset. Years of marriage only accounts for 18% of why marital infidelity occurs. That leaves 82% unexplained. In addition, the dataset is a composition of two surveys dating 47 years and 52 years ago. It raises a question in regards to generational subjects. For instance, the survey from Psychology Today dates from 1969. The survey from Redbook dates 
from 1974. A lot has changed both in terms how people view marriage and its purpose. Perhaps 
recent studies that predict happiness rating and religiousness as predictors of infidelity used a 
sample from a more recent generation than the one used by Fair. More research is needed to 
determine if a more recent generation plays a role in predicting marital infidelity predictors. 



##### [ GitHub Repository [Link](https://github.com/RenaissanceMan06/Marital_Infidelity) ]

## Reference

Whisman, M. A., Gordon, K. C., & Chatav, Y. (2007). _Predicting sexual infidelity in a 

_population-based sample of married individuals_. Journal of Family Psychology, 21(2), 320–324. 


