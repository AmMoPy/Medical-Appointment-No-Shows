## Introduction

The dataset includes medical appointment status as well as some patient details of Brazilian families; I'd be interested in investigating the reason why some patients do not show up to their scheduled appointments and whether there are opportunities for improvement in appointment administration that would result in a higher attendance frequency.

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

## Conclusion

1. Females and Senior age group have higher attendance frequency than others
	
2. Youth age group most likely will skip their medical appointments
	
3. Enrolment in Bolsa Familia program, hypertension and diabetes medical conditions are common characteristics of patients with higher attendance frequency
	
4. Seniors and adults age group shows a slight improvement in attendance frequency with shorter lead times.

5. No preference for specific weekday over the other when it comes to attendance frequency.


## Appointment administration improvement opportunities 

1. Spread appointments across months and weekdays regardless of weekends.

2. Avoid scheduling multiple appointments in the same day for a single patient. Unless there is a need to.

3. Follow a systematic approach when sending reminders to patients and consider increasing the frequency and/or methods of reminders while closely monitoring the associated costs of doing so.
	

## Limitations
	
- How was the appointment scheduled is not clear.
	
- Sufficient details about appointments are not provided (Type, employee ID, physician, venue, etc…).
	
- Medical history of children has some unusual entries like alcoholism. I did not disregard this.
	
- Count and timing of sms reminders are not provided
	
- I assumed age of 0 relates to newborns and not data entry error

- Appointment administration and related data anomalies can lead to different interpretations if proved to be valid, actually it casts doubts on the integrity of the whole dataset.
