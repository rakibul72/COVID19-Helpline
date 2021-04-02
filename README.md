# COVID19-Helpline

1. Introduction:
The name of our project is COVID-19 Helpline.It will help mass people by providing COVID-19 emergency
services and information.They will get all the information related to Plasma,Oxygen,Doctor,ICU and Ambulance.
People can get easy access to the much needed services and information at the time of emergency in this
pandemic situation.


2. Objective:
Our goal is to help people by providing information and services at emergency moment.We are trying to
provide all the important information like Plasma,Oxygen,Doctor,ICU and Ambulance at one platform related
to COVID-19.At emergency moments people become more helpless and can not set their immediate action to
perform without proper information.Many lives can be saved by taking proper initiatives at the right time.We
are going to perform that duty by providing correct information and contribute to overcome this pandemic
situation.


3. Features:
Following is the main features of our project:
• Information about available Plasma Donors.
• Information about Oxygen providers and their stocks.
• Doctors information for emergency consultation.
• Information about available ICU’s at the hospitals.
• Emergency Ambulance service information.
• User Profile and information about users health.


4. Entity-Relationship Diagram:
Following are the possible Entities,Relationships and Attributes:
4.1 Entity and its attributes
Possible Entities are listed below:
4.1.1 Entity-01: User
• UserID
• UserName
• UserAge
• UserMobileNo
• UserAddress
• UserGender
• UserBloodGroup
• UserCovidStatus
• UserAffectedDate
• UserRecoveryDate
• DoctorID
• UserEmail
• UserPassword

4.1.2 Entity-02: Doctor
• DoctorID
• DoctorName
• HospitalID
• DoctorGender
• DoctorMobileNo
• DoctorAvailableDay
• DoctorAvailableTime

4.1.3 Entity-03: Hospital
• HospitalID
• HospitalName
• HospitalAddress
• HospitalContactNo
• NumberOfICU
• NumberOfAmbulance

4.1.4 Entity-04: Ambulance
• AmbulanceID
• HospitalID
• AmbulanceMobileNo
• AmbulanceAvailability
• AmbulanceRent

4.1.5 Entity-05: Plasma
• UserID
• DonorStatus

4.1.6 Entity-06: OxygenProvider
• ProviderID
• ProviderName
• ProviderAddress
• ProviderContactNo
• ProviderAvailableStock
• PricePerUnit

4.1.7 Entity-07: ICU
• ICUID
• HospitalID
• ICUAvailability
• CostPerDay


4.2 Relationship:
Possible Relationships are listed below:
4.2.1 Relationship-01: Assigned
Between User and Doctor entities.

4.2.2 Relationship-03: Donate
Between User and Plasma entities.

4.2.3 Relationship-04: Buy
Between User and OxygenProvider entities.

4.2.4 Relationship-05: Work
Between Doctor and Hospital entities.

4.2.5 Relationship-06: Owns
Between Hospital and ICU entities.

4.2.6 Relationship-07: Has
Between Hospital and Ambulance entities.


5. Conclusion:
The user will get all the necessary information in one platform.It will be very helpful for the people in this
pandemic situation.We hope that this software will fulfill the needs of information and services by interaction
between the users of this platform.
