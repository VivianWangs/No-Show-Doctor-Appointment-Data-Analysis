# No Show Doctor Appointment Exploratory Analysis 



This is a dataset collecting 100K medical appointments in Brazil regarding whether patients show up in their appointmnet or not. It collects the following patients' information:

PatientId: ID of patient AppointmentID: ID of appointment
Gender
ScheduledDay: the Date patient set up their appointment
AppointmentDay: the Date patient visit doctor
Age: patient's age
Neighbourhood: location of hosipital
Scholarship: Brazil benifit provide to low income family
Hipertension: patient's sympton
Diabetes: patient's sympton
Alcoholism: patient's sympton
Handcap: patient's sympton
SMS_received: whether received SMS reminder regarding appointmnet
No-show: yes for no-show and no for show




The data was cleaned and analyzed by pandas and visulization by matplotlib. Two interesting observations were found in this work:

- Female has a slightly higher chance to no shown in a scheduled doctor appointment.
- The appointments with longer gap between appointment day and scheduled day are likely to have more no show occurrance. This ratio peaks at 20-50 day gap but start to decrease when it is longer than 50 days.






