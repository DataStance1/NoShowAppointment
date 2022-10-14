# NoShowAppointment
An analysis done with python to find out factors that contributes to Patients keeping to medical appointments in a hospital in Brazil

## Introduction
### Dataset Description
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row. The dataset has 110527 rows and 14 columns. 'PatientId','AppointmentID', 'gender', 'scheduledday', 'appointmentday', 'age', 'neighbourhood', 'scholarship', 'hipertension', 'diabetes', 'alcoholism', 'handcap', 'sms_received', 'no-show'. ‘ScheduledDay’ tells us on what day the patient set up their appointment. ‘Neighborhood’ indicates the location of the hospital. ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família. The 'no-show' tells us if the patients showed up for the appointment.it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

## Question(s) for Analysis
1. Are patients that show up for appointments older or younger?
2. Does Gender have a role to play in meeting appointments?
3. Does sending a reminder help patients meet appointments?
4. Do patients on scholarship meet appointments more than those that are not?

## Conclusions
* From the analysis, holder patients were found to meet appointments more than younger ones though this difference is not strong and requires further statistical analysis to back it up.

* The gender of the patients has little or no effect on whether the patients meets an appointment or not.

* The effect of sending sms on patients ability to meet appointments can not be ascertain with information on the dataset or descriptive statistics. it can not be categorically said that patients that recieve sms meet appointment more or that patients that receive sms meet appointment because of the sms. Further statistical test should be done to arrive at that conclusion.

* It can be deduced from the analysis most patients that meet appointments are not on the scholarship program. Just a few of the patients on the scholarship meet appointments

* A major limitation of the analysis is the scope of the data. Additional information were needed to answer some questions. Also, the analysis was limited to only descriptive statistics. To make predictions and arrive at some conlcusions, inferential analysis and machine learning has to be employed
