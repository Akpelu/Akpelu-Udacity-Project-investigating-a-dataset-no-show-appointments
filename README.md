# UDACITY Data Analysis Nanodegree Project: 01: Investigating-a-dataset-no-show-appointments
# Dataset Description:
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row. ‘ScheduledDay’ tells us on what day the patient set up their appointment. ‘Neighborhood’ indicates the location of the hospital. ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família. ‘No_Show’: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

# Summary
I investigated this dataset by employing diferent wrangling methods and visualizations using Python.

# Question(s) for Analysis
- What are the total Number of Patients who showed-up vs Patients who did'nt show-up

- What factor is associated with patients' attendance ('Age', 'being alcoholic','Having an SMS', 'Gender', 'Scholarship'), to make the patient make it to his appiontment?

# Limitation
We ought to also consider the how patients' distance from work place or home to the hospital influence their attendance.

# Conclusions
From our analysis;

- For the patients scheduled for Doctors appointment, those who showed up and those who didn't were 79.8% and 20.2% respectively. Meaning more patients showed for the appointment.
- The patients who showed up for the appointment are almost the same as people who are alcoholic. Meaning Alcohol intake has no influence on the attendance.
- Gender and Alcoholism didn't influence the attendance. As such, not a factor to consider for the analysis.
- Few people who are on scholarship didn't show up for the appointment. Meaning that most patients didn't show up because they are on scholarship.
- Older patients showed up more for the doctor's appointment. With an average of 37.79 showing up and average of 34.31 not showing up for the appointment. Meaning Age is an important factor to consider from our analysis.
- Patients with diabetes showed more. Meaning Diabetes is associated with age.
