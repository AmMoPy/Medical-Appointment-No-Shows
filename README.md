## Introduction

Why do 30% of patients miss their scheduled appointments?

This is an EDA and prediction modeling for a dataset that includes medical appointment status as well as some patient details of Brazilian families; I'm investigating the reason why some patients do not show up to their scheduled appointments and whether there are opportunities for improvement in appointment administration that would result in a higher attendance frequency.

The dataset consists of 14 variables as follows:

1. PatientId : Unique identification of a patient
2. AppointmentID : Unique identification of each appointment
3. Gender: Male or Female.
4. ScheduledDay: The day of registering the appointment.
5. AppointmentDay: The day of actual appointment.
6. Age: How old is the patient.
7. Neighbourhood: Where the appointment takes place.
8. Scholarship: Whether the patient is enrolled in [Bolsa_Família](https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia), which is a social welfare program of the Government of Brazil
9. Hipertension: Hypertension, also known as high blood pressure. Part of patient's medical history.
10. Diabetes: Part of patient's medical history.
11. Alcoholism: drinking of alcohol that results in significant mental or physical health problems. Part of patient's medical history.
12. Handcap: handicap, part of patient's medical history.
13. SMS_received: frequent reminders of scheduled appointment.
14. No-show: whether the patient made the actual appointment or not. 'Yes/True' means the patient did not make the appointment.

Several questions will be addressed:

1. Factors driving higher attendance frequency? is it age, gender, medical history or enrollment in Bolsa Família program?

2. Does time has an impact on attendance frequency?

3. Are there certain neighborhoods experiencing higher attendance frequency than others? Why?

4. Is appointment scheduling administered properly?
	
Main dependent variable is appointment status 'No-Show’; rest will be the independent ones.
