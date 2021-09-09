# Investigate the features that may affect showing up for their appointment

## Introduction
The dataset I choose is Medical Appointment No Shows.(Original source on [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments)) 110.527 medical appointments its 14 associated variables (characteristics). The most important one if the patient show-up or no-show to the appointment. I would focus on the features of people who show-up or no-show, and find the trend that will affect patient's decision.

## Conclusions
To sum up, four features are selected to discuss and here are the result.

> 1. SMS do not increase attendance rate, even decrease.
**Suggestion**: Adjust the content of sms or use a phone call instead of sms, and adjust sms sending time to the appointment day.  
>
>2. People whose scheduled day and appointment day are the same day have the highest attendance rate and the no-show rate seems to have a positive correlation with days between scheduled day and appointment day.   
**Suggestion**: Send everyone a sms at the appointment day. Remind them when do they head to medical occasion.  
>
>3. There are no obvious difference on Age and Gender distributions of show up and no-show groups.   
**Suggestion**: Maybe children can not go to medical occasion themselves, so this column is less meaning for attendance rate.

There are 110527 samples in this dataset, I think is enough to represent that region but not whole country. However, there are some shortcomings I would like to talk about.
>1. Some columns are quite useless such as neighbourhood. The scheduled medical occasions are not documented so we can't calculate the distance. I think maybe long distance between neighbourhood and medical occasion would affect attendance.
>2. An another limitation is we can not tell whether the person scheduled this appointment in person. If the other person help it, we can not ensure the information they input is right.
>3. For now, I don't kbow how to use more advanced statistic method such as two-sample test, anova test. Therefore, the statistic is not much professional. 

## Reference
web site:
- https://numpy.org/doc/stable/index.html
- https://pandas.pydata.org/docs/index.html
- https://matplotlib.org/stable/index.html
- https://github.com/matplotlib/matplotlib/issues/13803
- https://stackoverflow.com/questions/45057647/difference-between-axisequal-and-axisscaled-in-matplotlib
- https://stackoverflow.com/questions/55268098/python-valueerror-too-many-values-to-unpack-expected-2

book:
- Python for Data Analysis, 2nd Edition by Wes McKinney