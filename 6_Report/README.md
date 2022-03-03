# Requirements
## Introduction
 This project is the implementation for “ HOSPITAL MANAGEMENT SYSTEM” is a program developed for managing details regarding number of patients entering to the hospital. The program is very helpful to find the results of the inpatients and outpatients easily. we can search the doctors related to patients in hospital demo. The project and implementation is developed by using c.  There’s  login system available for this system, the receptionist login into the system and use resources.

## Research

About Hospital Management System C Project:

---Add new patient record: In this feature, user can add a new patient record
---Search or edit patient record.
---List record of patients.
---Delete patient records'
---Exit from the system
 
## Cost and Features and Timeline

1.Time-saving Technology
2.Improved Efficiency by avoiding human errors
3.Reduces scope for Error
4.Data security and correct data retrieval made possible
5.Cost effective and easily manageable
6.Easy access to patient data with correct patient history
7.Improved patient care made possible
8.Reduces the work of documentation

## Defining Our System
    Here in our project(Hospital management system) user can able to login and should enter password then main menu will be display .The login password would be declared default.
    Now user can add new patient record,delete existing patient record, update existing records, view list existing records etc. Finally user can exit from system.
## SWOT ANALYSIS
<h3>Strengths

•	A primary focus on quality improvement ($ saved from quality projects)
•	Internal teams dedicated to research and analytics ($ spent on research)
•	High-quality medical personnel (# of staff with external recognition)
•	Modern medical equipment and a well-equipped facility (average age of medical equipment)

<h3>Weakness

•	Outdated healthcare facilities and technology
•	Insufficient management training
•	Lack of funding and resources to support programs
•	Poor location that’s not easily accessible for staff and patients
•	High staff turnover

<h3>Opportunities:

•	Collaborate with different healthcare organizations to knowledge share
•	Develop healthcare programs and initiatives to drive more community outreach and engagement
•	Increase funding for analytics and researching, including both staff and technology
•	Create mentor programs

<h3>Threats:

•	Economic or political insecurity
•	Policy and legislation changes that result in budget deficits
•	Pressure to reduce costs while meeting expectations of universal healthcare coverage
•	Increased competition from newly built hospitals

## Who
The implementation of hospital management system project provides the institution with different advantages that improve the service quality and efficiency. As mentioned above it is created a user can handle: patients details, recordsf and management, and third-parties like drug suppliers and insurance companies.

## What
The hospital management system helps register complete patient information. It captures and stores the medical history, treatment required, details of their previous visits, upcoming appointments if any, reports, insurance details and more. It helps eliminate the need to get these details on every visit.

## When
HMS information system helps to track and control finances, reduce leakages as well as reduce manual work and therefore there is no requirement of the higher human workforce.

## Where
Hospital Management System helps the professionals in healthcare to check out the clinical documents, diagnosis, patient records, and other relevant things at a single view and therefore results in the healthcare professionals to make decisions at the right time

## How
    The system creates an external file to store the data perminantly.This system is deployed using c programming.

## High Level Requirements
| **<h3> ID** | **<h3>Description**                                              | <h3>Status      |    
|-------------|--------------------------------------------------------------|------------- |
 | Patient Activities|-It includes patient records,patient information  | Implemented    |
| Adminstration     |It includes room informtion,general adminstration| Implemented    |
|  Payment Details       |It includes patient payment details,pay recipts etc| future    |
##  Low level Requirements
 | **<h3> ID** | **<h3>Description**                                              | <h3>Status      |    
|-------------|--------------------------------------------------------------|------------- |
 | security|It should secure because  only authorized user or receptionist can this system  | Implemented    |
| platform     |The system can be work on any operating system like windows or linus| Implemented    |
|  Performanace       |The system should handles the large amount patients data| Implemented    |


# Design
## High Level Design 
 Class Diagram( Structural)
![class diagram](https://user-images.githubusercontent.com/54410419/132119045-95eee289-bc6c-4abf-bbbe-9b8f99fa0705.jpg)
Activity Diagram( Behavioural Diagram)
![activity diagram](https://user-images.githubusercontent.com/54410419/132119065-261ef638-2406-4db0-948b-965fe8630b2f.jpg)
## Low Level Design 
 Deployment( Structural) 
 ![deploymentdiagram](https://user-images.githubusercontent.com/54410419/132119107-f6fad45d-1c68-4720-983a-32ebd74381d0.png)
Use case ( Behavioural Diagram)
![usecase](https://user-images.githubusercontent.com/54410419/132119114-ac043abe-8c2a-4cb4-894b-12c11763ad00.jpg)
 
 
## Test Plan

## High Level Test Plan

| Test ID | Description | Exp I/P | Exp O/P |	Actual Output | status |
| --- | --- | --- | --- | --- | --- |
| H_01 | Adding new patients details  | id,name | Record ipdated sucessfully | Record ipdated sucessfully | pass |
| H_02 | Delete existed  patient  record | id=? | id found | id found | pass | 
| H_03 | checking list records present in system| view records | list of records | list of records | pass |
| H_04 | Search for particular patient record in system  | enter patient id | Record found | Record found | pass |
| H_05 | checking rooms availability | Room no | Room available | Room availble | 
| H_06 | Login into the system | Password | Accepted |Accepted| pass |
| H_07 | Exit from the system | Exit | Exited | Exited | pass |


## Low Level Test Plan



| Test ID | Description | Exp I/P | Exp O/P |	Actual Output | status |
| --- | --- | --- | --- | --- | --- |
| L_01 | Delete patient record not existed  | id | id not found | id not found | pass |
| L_02 | Login into the system | Password | Denied | Denied | pass | 
| L_03 | checking rooms availability| Room no | Room not available | Room not available | pass |



## Exit test case output

![test_exit](https://user-images.githubusercontent.com/54410419/132303815-991d0b57-89f6-4bfa-b2ef-348edeb25366.PNG)
