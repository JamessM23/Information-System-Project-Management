* Project: All in One Care 
* Version: 1.0
* Date: 09.17.2026
* 1. Introduction
* 1.1 Purpose
* The purpose of this Software Requirements Specification (SRS) is to define the functional and non-functional requirements for CareConnect, a patient-centered healthcare management application.
* 1.2 Scope
* The scope of the All in One Care project is to develop a healthcare management application that helps patients organize important healthcare information in one place. The application will include features such as appointment tracking, medication reminders, healthcare information, notifications, and caregiver access. The project will focus on creating a simple and secure system that improves how users manage their everyday healthcare tasks. The initial project will not include medical diagnosis, treatment recommendations, or emergency medical services. 
* 2. Overall Description

## 
    1. Users


All in One Care will have several groups of users who will interact with the application:



* Patients: The primary users who will use the app to manage appointments, medications, reminders, and healthcare information.
* Caregivers/Family Members: Users who have been given permission by a patient to help manage their healthcare information and appointments.
* Healthcare Providers: Authorized providers who may eventually interact with patient information or appointment-related features.
* System Administrators: Users responsible for managing accounts, maintaining the system, and addressing technical issues.

## 
    2. System Environment


All in One Care will be developed as a mobile and web-based application. Users will be able to access the application through a smartphone, tablet, or computer with a supported web browser. The system will require an internet connection to access cloud-based information and services.

The application will use a database to securely store user accounts, appointments, medication schedules, and other information. The system may eventually connect with external healthcare systems through APIs.


## 
    3. Constraints

The All in One Care application will have the following constraints:



* Users must have a compatible smartphone, tablet, or computer to access the application.
* Users must have internet access for the application to function.
* Users must create an account and authenticate before accessing personal healthcare information.
* Certain features will require users to have the appropriate permissions.
* Caregiver access must be authorized by the patient.
* The application must protect sensitive healthcare information through appropriate security measures.
* The initial version will have a limited number of features due to project time and development resources.

## 
    4. Assumptions


The project assumes that:



* Users will have access to the internet.
* Users will have a compatible device and supported web browser or mobile application.
* Users will provide accurate information when creating their accounts and entering healthcare information.
* Users will keep their login credentials secure.
* Users will have the appropriate permissions to access healthcare information.
* External healthcare system integration may not be available during the initial version of the project.
* Users will understand that CareConnect is a healthcare-management tool and does not replace professional medical advice.
  
  ## 
    Functional Requirements


Functional requirements describe what the system will do.



1. User Login: The system shall allow users to create an account and securely log in.
2. Appointment Management: The system shall allow users to add, view, edit, and delete healthcare appointments.
3. Medication Reminders: The system shall allow users to enter medications and set reminders for when they need to be taken.
4. Healthcare Information: The system shall allow users to store and view important healthcare information in their account.
5. Caregiver Access: The system shall allow patients to give authorized caregivers access to selected healthcare information.

## 
    Non-Functional Requirements


Non-functional requirements describe how well the system should work.



1. Security: The system shall protect user healthcare information and require authentication before accessing private information.
2. Performance: The system should load pages and respond to user actions within a reasonable amount of time.
3. Usability: The application shall have a simple, easy-to-understand interface that can be used by people with different levels of technical experience.
4. Availability: The system should be available whenever users have an internet connection, except during scheduled maintenance or unexpected outages.
5. Compatibility: The application shall work on supported smartphones, tablets, and computers using common web browsers.

   
    All in one care use cases
   
UC-01 Create Account Patient User creates a new CareConnect account.

UC-02 Log In Patient/Caregiver User logs in to securely access the application.

If a Patient/Caregiver User is unable to log on to their account, they can use UC-03 Reset Password Patient/Caregiver User to reset the password.

UC-04 View Dashboard Patient/Caregiver has the upcoming appointments and medication reminders and notifications on its main dashboard.

UC-05 Add Appointment Patient User: Adds a new healthcare appointment to their account.

UC-06 Edit Appointment Patient User – edits the details of an appointment.

UC-07 Delete Appointment Patient User deletes an appointment that has been canceled, or is incorrect.

UC-08 Add Medication Patient User adds a medication, dosage, and schedule to their account.

UC-09 Set Medication Reminder Patient User creates a reminder for when they need to take a medication.

UC-10 Update Medication Patient User makes changes and/or removes details of an existing medication.

UC-11 View Healthcare Information Patient User can access their saved healthcare information via the application.

UC-12 Update Healthcare Information Patient User uploads or updates healthcare information in their account.

A family member or caregiver is able to access certain information using the UC-13 Add Caregiver Patient User.

UC-14 Manage Caregiver Permissions Patient Patient will determine what information the authorized caregiver will have access to.

UC-15 Receive Notifications Patient/Caregiver User will get reminders and notifications for appointments, medications and other healthcare-related tasks. 
