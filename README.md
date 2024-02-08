# Entity Relationship Diagram (ERD)
Entity Relationship Diagram examples with solutions.


# Case 1
A big company has decided to store information about its projects and employees in a database. The company has wisely chosen to hire you as a database designer. Prepare an E-R diagram for this Company according to The following Description:</br>
•	The company has a number of employees each employee has SSN, Birth Date, Gender and Name which represented as Fname and Lname.</br>
•	The company has a set of departments each department has a set of attributes DName, DNUM (unique) and locations.</br>
•	Employees work in several projects each project has Pname, PNumber as an identifier, Location and City.</br>
•	Each employee may have a set of dependent; each dependent has Dependent Name (unique), Gender, and Birth Date.</br>
  Note: if the employee left the company no needs to store his dependents info</br>
•	For each Department, there is always one employee assigned to manage that Department and each manager has a hiring Date </br>
•	Department may have employees but employee must work on Only One department</br>
•	Each department may have a set of projects and each project must assigned to one department</br>
•	Employees work in several projects and each project has several employees and each employee has a number of working hours in each project</br>
•	Each employee has a supervisor 

![image](https://github.com/NouraAlgohary/Entity-Relationship-Diagram-ERD-/assets/103903785/0432cee1-7e36-4dce-8ef1-66d7b03bf974)

# Case 2
(Note that the Identification number is unique)  </br>

Musicana records have decided to store information on musicians who perform on their albums in a database. The company has wisely chosen to hire you as a database designer.</br>
•	Each musician that is recorded at Musicana has an ID number, a name, an address (street, city) and a phone number.</br>
•	Each instrument that is used in songs recorded at Musicana has a unique name and a musical key (e.g., C, B-flat, E-flat).</br>
•	Each album that is recorded at the Musicana label has a unique title, a copyright date, and an album identifier.</br>
•	Each song recorded at Musicana has a unique title and an author.</br>
•	Each musician may play several instruments, and a given instrument may be played by several musicians.</br>
•	Each album has a number of songs on it and song must appear on one ablum.</br>
•	Each song is performed by one or more musicians, and a musician may perform a number of songs.</br>
•	Each album has exactly one musician who acts as its producer. A producer may produce several albums.</br>
Design a conceptual schema for Musicana. Be sure to indicate all keys and cardinality constraints and any assumptions that you make.</br>

![Problem 1 - P1 - Musicia](https://github.com/NouraAlgohary/Entity-Relationship-Diagram-ERD-/assets/103903785/05699a01-f325-449a-b88e-57e9eb329689)


# Case 3
Prepare an E-R diagram for a reaP2l estate firm that lists properties for sale. The following describes this organization:</br>
•	The firm has a number of sales offices in several states. Attributes of sales office include Office_Number and Location.</br>
•	Each sales office is assigned zero or more employees. Attributes of employee include Employee_ID  and Employee_Name. An employee must be assigned to only one sales office.</br>
•	For each sales office, there is always one employee assigned to manage that office and manager can’t manage many sales office at the same time. </br>
•	The firm lists property for sale. Attributes of property include Property_ID and Location. Components of Location include Address, City, State, and Zip_Code.</br>
•	Each property must be listed with one (and only one) of the sales offices. A sales office may have any number of properties listed, or may have no proper¬ties listed.</br>
•	Each property may have zero or more owners. Attributes of owners are Owner_ID and Owner_Name. An owner own one or more properties. The system stores the percent owned by each owner in each property.</br>

![Problem 1 - P2](https://github.com/NouraAlgohary/Entity-Relationship-Diagram-ERD-/assets/103903785/677f3283-8f2a-4c4c-b88e-64a37449402f)

# Case 4
•	A General Hospital consists of a number of specialized wards. Each ward is described by ward_id, Name</br>
•	The system records the following details about patients: Patient_id, name, Date_Of_Birth</br>
•	Each ward may host more patients and each patient is hosted by only one ward.</br>
•	Each patient is assigned to one leading consultant but may be examined by other consultants, if required. </br>
•	Each consultant may be assigned zero or more patients and may examine zero or more patients.</br>
•	Consultants are described by Consultant_id, Name</br>
•	The system has to record all required data each time the Nurse gives a patient a certain drug with specified dosage at certain date and time.</br>
•	Each ward is under supervision of one nurse and a nurse may supervise only one ward. </br>
•	Each Nurse must serve in one ward and ward can have many nurses.</br>
•	Data about the nurse is recorded as her name and her number and her address.</br> 
•	A drug has code number, recommended dosage and more than one brand name.</br>

![ERD-Page-4 drawio](https://github.com/NouraAlgohary/Entity-Relationship-Diagram-ERD-/assets/103903785/18e5b74c-d540-4804-952f-47f664b8b19d)


# Case 4
Major airlines companies that provide passenger services keep database with lots of information on all airlines.</br>
1. Each airline has an identification number, name and address, name of the contact person and telephone numbers.</br>
2. Each employee works in Airline Company has an employee identification number, name, address, birthday recorded as (day, month, year), gender, position with the company, and qualifications.</br>
3. Each airline owns different aircrafts. For each aircraft an aircraft identification number, capacity, and model is recorded.</br>
4. The aircrafts are assigned to different routes. An aircraft can work on more than one route and a route has many aircrafts going on it. Some information as number of passengers, price per passenger, departure date time, arrival date time and the time that aircraft spent in travelling the route are recorded.</br>
Each route has a route identification number, origin, destination, distance,classification (e.g. domestic or international route).</br>
5. Each aircraft has its own crew (major pilot, assistant pilot and two hostesses), the aircraft crew not stored as employee. Each crew is assigned to only one aircraft.</br>
6. Each airline keeps information about their buy/sell transactions (for example selling an airplane ticket is a sell transaction, paying for maintenance is a buy transaction). Each transaction has a transaction identification number, date, description, and amount of money paid/received. </br>
                                                                                                                  
![Problem 1](https://github.com/NouraAlgohary/Entity-Relationship-Diagram-ERD-/assets/103903785/4c5c099a-8612-4cb0-902c-870721bc0a6f)

