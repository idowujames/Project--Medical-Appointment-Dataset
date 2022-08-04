# Project--Medical-Appointment-Dataset
Analyse a dataset to know which variables will determine if a patient will show up for their appointment.

This was a udacity course work as part of earning the data analyst certificate

### Dataset Description 
> This dataset contains information from 100k plus medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment.

**The variables represented in this dataset are:**


> **01 - PatientId** : Identification of a patient , 
**02 - AppointmentID** : Identification of each appointment , **03 - Gender** :
Male or Female , **04 - AppointmentDay** : The day of the actual appointment , **05 - ScheduledDay** : The day someone called or registered the appointment , **06 - Age** : Patient's Age , **07 - Neighbourhood** : Were the appointments is taking place , **08 - Scholarship** : True of False(Bolsa Família Scholarship), **09 - Hipertension** : True of False , **10 - Diabetes** : True of False , **11 - Alcoholism** : True of False , **12 - Handcap** : True of False , **13 - SMS_received** : 1 or more messages sent to the patient , **14 - No-show** : True of False

## **Questions for Analysis**


*1) How much does age play in whether a person will show up for their appointment**


> ***Rational:*** Younger people tend to prioritize other things over their health. I will try to findout if younger people who are above the age of parental guidance have a higher percentage of missing appointments than other age groups

*2) How much does the time difference between the date appointment was made and the actual date of the appointment play in whether a person will show up for their appointment**


> ***Rational:*** According to the behavioural sciences, the time intervel between intention and behaviour plays a significant role in behaviour. I intend to find out whether the longer between the day the appointment was made and the actual appointment date makes any significant difference in the patient's showing up. 
I will also investigate if this time interval of no show is affected by the patient's age.
