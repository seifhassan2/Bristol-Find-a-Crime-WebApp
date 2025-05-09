# Requirements

## User Needs

### User stories

- As an international student, I want to get to know more about Bristol’s different neighbourhoods' crime history. So that I can choose the safest place I should stay in during my studying period to avoid risks. I want to stay away from danger and feel like home during my residence in Bristol.

- As a UK Home Student, I want to know if the place I am living at is the safest place to live by knowing the history of the place. The place of study should not distract or put me in danger during my time being there. I want something that will display the neighbourhood's past and in what area of Bristol I should avoid. This should benefit me by letting me use a tool for such a use. 

- As a new resident moving to Bristol for a new workplace, I want to search for the safest place to stay in Bristol. So that I can be in a convenient environment and go to my work safely.

- As a resident, I want to report an incedent or a crime I have experienced in my neighbourhood, so that I can spread conscious and get engaged to spread crime awareness to my community.

- As a researcher, I want a reliable website that provides statistical data for Bristol's neighbourhoods' crimes history, so that I can benefit from it in my research about crimes in Bristol.  



### Actors

-	International students: We focus mainly on international students who come from their home countries and search for accommodation to stay in during their period of studying. They will need to be provided with information about the place/ neighbourhood they intend to go to.
-	Second, third year students and postgraduates: they will not be in the university halls so they will need a place to stay. This tool will be helpful for safety reasons.
-	New residents (families or individuals): As they are moving to a new different city (Bristol), they need to seek the safest places to live in.
-	Neighbours: Neighbours are given the chance to show the different types of crimes that can be shown, can be reported. 
-	Researchers and Criminology enthusiasts: this is a tool to show data, anyone can go on the website out of curiosity. Researchers can be involved on the website for their studies.
-	(Theoretically) police: they can see what areas will need to be worked on to make these areas safer.


### Use Cases

| USE-CASE ID: UC1 (By: Seif Hassan)| USE-CASE NAME: Find a Crime | 
| -------------------------------------- | ------------------- |
| **Description** | A student trying to search for the crime history of the area that he intends to move to in Bristol during his university studies 
| **Actors** | International/UK Home Student |
| **Assumptions** | Pre-condition: Internet access available and basic knowledge of how to use a web application. <br> Post-condition: The student identifies the neighborhood based on the provided crime data. |
| **Steps** | 1- User Action: The student navigates to the website's home page. <br> 2- The student presses the Find a Crime button <br> 3- The system displays a search bar and an interactive map of Bristol. <br> 4- The student enters the name of a neighborhood, street or crime type. <br> 5- The system displays on the the crimes that happened in the chosen area <br> 6- The student reviews the data to assess whether his chosen neighborhood is safe for residence or not. |
| **Variations** | The student may choose to filter the results by a specific time range |
| **Non-functional** | The system should load results in under 3 seconds. |
| **Issues** | The student may choose a location that is out of our data set used. |


#


| USE-CASE ID: UC2 (By: Seif Hassan) | USE-CASE NAME: Report a crime | 
| -------------------------------------- | ------------------- |
| **Description** | A resident trying to report a crime he experienced in a certain neighbourhood in Bristol. We receive the information and add it to our database. So anyone can be aware of that |
| **Actors** | Current resident in Bristol |
| **Assumptions** | Pre-condition: <br> Internet access available. <br> Report button available. <br> Filters to choose the type of crime, date, and location. <br> a Comment box available for the user to add more details if he wants <br> post-condition: <br> The user clicks on the report button in order to add his report of a crime in the reports section. |
| **Steps** | 1- The user opens the Web App leading him to the home page. <br> 2- User navigates to the report a crime page by clicking "Report a crime" button in the home page. <br> 3- User fills a form for gathering information of the crime area, crime type and crime date. <br> 4- User adds more details in the comment box below the categories options. |
| **Variations** | Users can upload photos or videos as evidence. |
| **Non-functional** | The system must ensure data security and user privacy. |
| **Issues** | Verifying the authenticity of user reports. |

-------------------------------------------------------------------------------------------

![Use-Case Diagram Here](REQusecased.png)

#

| USE-CASE ID: UC3  (By:Tyler Dixon ) | USE-CASE NAME: Search filter | 
| -------------------------------------- | ------------------- |
|Use-CASE ID: UC3	USE-CASE: Crime search filter
Description	Will be able to search the rime based on the different types of column set out on the filter

Actors	Residents of Bristol. Everyone on the website can make sure the different types

Assumptions	Pre-condition:
•	Website accessed 
•	search in the crime
Post-conditions:
•	the table given should be able to output the results given on the search criteria

Steps 	1.	User will access the website
2.	Able to type on the website
3.	Results should be present
Variations	All crimes on the website should output all results 

Non-functional	The search criteria should output all results

Issues 	The search bar will be glitched upon entry

![image](https://github.com/user-attachments/assets/8db2f82a-a4fb-4159-ab3f-f72b72391030)

---------------------------------------------------------------------------------------------

USE-CASE ID: UC4 (By Tyler Dixon)	UAE CASE NAME: Removing of reports
Description 	User will make a “false” report for it to be remove under false information
Actors	Anyone “Users”/ Admins 
Assumptions	Pre-condition: user will be aware under the rule

Post-condition: The post will be banned from the website and theoretically face consequences.

Steps	1.	User will access the website
2.	User will make a report about a false crime 
3.	Admin will confirm there was not a crime 
4.	The ban will be inflicted onto the user
5.	The user will face consequences 
Variations 	The user will be either banned or warned based on the numerical times make such offences 

Issues 	Crimes will take time for it confirmed

Non-functional 	The report must be able to function through a request


![image](https://github.com/user-attachments/assets/4c531afe-e88f-414d-8c39-661012caf652)


-----------------------------------------------------------------------------------------------


## Software Requirements Specification
### Functional requirements
    
FR1.1: The system MUST allow users to search for specific neighborhoods in Bristol by name on a map. (Search Functionality) (UC1) <br> FR1.2: The system SHOULD provide filters to narrow down data by time range (e.g., last month, last year) and type of crime (e.g., theft, assault). (UC1) <br> FR1.3: The system MUST get the crimes data from crimes dataset used from Bristol Open Data. (UC1) <br> FR1.4: The system COULD provide real-time updates on ongoing crimes depending on resource limitations and data availability constraints. (UC1) <br> FR1.5 / FR2.1: The system WON'T allow direct interaction with police systems or data submission due to legal and technical complexities. (UC1) (UC2) <br> FR2.2: The system MUST allow users to report incidents and new crimes. (UC2). <br> FR2.3: The system COULD update the crime data based on user reports. (UC2). <br> FR1.6 / FR2.4: The system SHOULD ensure data accuracy and reliability. (UC1) (UC2). <br> 

#

UC3&UC4

Search filter
FR1: People on the website should be able to access the need website without an issue.
FR2: The website should get diferent types of data based on the API so that the criteria should be matched as shown by the person
FR3:Search filters would need to return certain types of results given by the user.
FR4: Search filters will need to filter all types of crimes if it meant no search critieria is given
FR5: The system should make a competent effort to not fail nor glitch upon entering input reporting of crime
FR6: the system should be able to send false crime reports but is theoretically punished
FR7: System should be able to allow the different admins to review the the crimes to the website's integrity
FR8: The system should make sure the admins can verify that the app is given a signal to know that the crime is false
FR9: The system should let the user of the consequences of giving a fabricated crime to the system



#


### Non-Functional Requirements

- NFR1.1: The system should load and display data within 3 seconds. (UC1) Performance
- NFR1.2: The system could handle up to 10,000 concurrent users without performance degradation. (UC1) Performance
- NFR2.1: The system could protect user data with encryption. (UC2) Security
- NFR2.2: The system could comply with relevant data protection regulations. (UC2) Security
- NFR1.3 / NFR2.3 : The system must be intuitive and easy to use for all user types. (UC1, UC2) Usability
- NFR1.4 / NFR2.4: The system could provide help and support features for users. (UC1, UC2) Usability
- NFR2.5: The system should allow for easy integration of new data sources. (UC2) Scalability
  #
- NFR8: The system should comply to the laws of GDPR so that not all data is available (UC3&4) Security
- NFR9: The system should allow significant updates without a prolonged amount of time (UC3&4) performance
- NFR10: The system should notify the user of the said updates(UC3&4) Usability
- NFR11: The system should be up nearly all the time except the update(UC3&4) Scalablity
- NFR12: The system needs to rejects any malicious hacking techniques such as SQL injection and CSRF attacks etc.(UC3)
- NFR13: Any data entered needs to be encrypted from all users(UC4) security
- NFR14: The must be easy to look at and easy to navigate; straight forward for anyone to use(UC3&4) Usability
  



