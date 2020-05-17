# Udacity--Investigating-Brazilian-medical-appointments
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row such as:

1. ‘ScheduledDay’ tells us on what day the patient set up their appointment.
2. ‘Neighborhood’ indicates the location of the hospital.
3. ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.

The analysis of this Data set revolves around finding ways to achieve the following:

What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?

### Research Question 1 : How many people visit the doctor on the scheduled day?
Answer : The number of people turning up for their scheduled appointment is around 80%.
The number of females in the given population of study is higher, there are 71839 females who make up 65% of the total population.
Almost equal percentage of males and females show up for their appointment (80%).

### Research Question 2 : Does the location of the hospital has an impact on the patient visits?
Answer : Yes

### Research Questio 3 :

The highest number of people who show up promptly for the appointment are the elderly. This is despite the fact that this group has the least number of beneficiaries of the health program.
Youths are the one's who skip their appointments the most though they received the most number of sms reminders.

### Research Question 4 :Which conditions (in the form of sms, health program or any ailments) sees the most number of people visiting on their scheduled dates.
Answer : 
1. Nudges: Even though people received sms reminders, they did not visit their doctors.
2. Ailments : People who have hypertension form the next highest category of patients who do not show up for their appointments.


## Conclusion
### Summary of statistical findings
Factors that help us predict whether the patient will turn up for the appointment or not:

#### On a general note:

1. 79.81% of the people turn up on the scheduled day of their appointments.
2. 20.19% of the people won't turn up.

#### Depending on 'gender':
1. The population under study comprises of 65% females and 35% males.
2. Percentage of females who show up for their appointment with the doctor : 79.68%
3. Percentage of males who show up for their appointment with the doctor : 80.03%
Hence we see that both males and females are equally-likely to visit the hospital on the scheduled day.

#### The locality factor:
The hospitals are located in 81 unique localities.

There are hospitals where the attendance of patients is on the lower side as compared to the rest (between 71 -78 %) and might need monitoring. Whereas there are localities in which hospitals see high patient turn outs (highest being around 91%).

#### Age:
The mean and median age of the population under study is 37 years. For the sake of analysis, we have created 4 age categories:

0-18 : Child/Teen

18-37 : Youth

37-55 : Mid-aged

55-115 : Elderly

#### The age group that :

1. Has the most number of people suffereing from alcoholism : middle aged men Has the most number of people suffering from hypertension and diabetes : Middle aged and elderly women

2. The age group that most promptly makes scheduled visit is the elderly. On the other hand, the youth needs nudging as they form the category that misses their appointments the most.

### LIMITATIONS :
1. The data set has a lot of categorical variables. There is only up to a point that high level statistical analysis can be performed on them.
2. We have mostly worked around descriptive statistics, for our analysis to be deeper : we need inferential tools. Regression models and sampling distributions can give us better insights about the dataset.
3. There can be a lot of inter-dependencies between the data. We can at times establish a correlation between two variables but that may not signify causality.
4. Also, we cannot eliminate the possibility of hidden variables. Hidden variables are those that are correlated with two variables who are in-turn not fundamentally related to each-other. This can sometimes lead to wrong causality linkages.
