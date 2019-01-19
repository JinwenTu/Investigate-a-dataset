# Investigate-a-dataset

In this project, I conducted my own data analysis of the  No-show appointments dataset (original source on Kaggle) and created a file to share my findings.

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row. A few points need special attention:

1. ‘ScheduledDay’ tells us on what day the patient set up their appointment.
2. ‘Neighborhood’ indicates the location of the hospital.
3. ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
4. Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

The analysis was following a few steps as below:

1. Take a look at the dataset and brainstorming what questions I could answer using it. The question I wanted to answer is what factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?

2. Use pandas and NumPy to answer the above question, and create a report sharing the answers. 
