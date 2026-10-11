# Files ending in (D1) are draft 1's iterations of the mockup.\
This iteration is focused on the **Scheduler** + **Check-In** aspect of the EHR. It includes:
  - a **Sign-In** screen with the option to **Check-In** a patient with a scheduled appointment or **Schedule** an appointment for a walk-in patient.
  - scheduling an appointment for a patient who has never been to the clinic before (**NEW** patient)
  - scheduling an appointment for a patient who has been to the clinic before and has a profile with their medical records (**CURRENT** patient)
  - checking-in a patient who has their first appointment scheduled for that day and does not have a profile with their medical records created yet (**INTERMEDIATE** patient)
  - checking-in a patient who has an appointment scheduled for that day (not their first appointment) and does have a profile with their medical records created (**CURRENT** patient)
\
\
# Files ending in (D2) are draft 2's iterations of the mockup.\
This iteration is also focused on the **Scheduler** + **Check-In** aspect of the EHR. It has the same concepts as **Draft 1's** but also takes into account additional edge cases not in **Draft 1**:
  - when to issue a **Ticket #** for a patient (only if they walk-in are scheduled for an appointment that same day)
  - removing the **Book Appointment** option from the **Intermediate** patients
    > this is since the **Intermediate** patient status is intended to be temporary for new patients who were not able to get an appointment the day they walked in. This is due to the volume of people going to clinic makes it not possible to create that patients' entire profile with their medical records at the desk when they schedule a future appointment.
