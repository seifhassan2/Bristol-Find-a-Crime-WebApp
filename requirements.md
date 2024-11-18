# Requirements

## User Needs

### User stories
TODO: Write brief user stories to explain how various actors would interact with the system to accomplish a goal.
    Express these in the form from agile development:- As a (role) I want (goal) so that (benefit).

- As an international student, I want to get to know more about Bristol’s different neighbourhoods' crime history. So that I can choose the safest place I should stay in during my studying period to avoid risks. I want to stay away from danger and feel like home during my residence in Bristol.

- As a student from the UK, I want to know if the place I am living at is the safest place to live by knowing the history of the place. The place of study should not have distracted me or put me in danger during my time being there. I want something that will display the neighbourhood's past and in what area of Bristol I should avoid. This should benefit me by letting me use a tool for such a use. 

- As a new resident moving to Bristol for a new workplace, I want to search for the safest place to stay in Bristol. So that I can be in a convenient environment and go to my work safely.


### Actors
TODO: List and describe the actors/users for this product.

-	International students: We focus mainly on international students who come from their home countries and search for accommodation to stay in during their period of studying. They will need to be provided with information about the place/ neighbourhood they intend to go to.
-	Second, third year and postgraduates: they will not be in the university halls so they will need a place to stay. This tool will be helpful for safety reasons.
-	(Theoretically) police: they can see what areas will need to be worked on to make these areas safer.
-	New residents (families or individuals): As they are moving to a new different city (Bristol), they need to seek the safest places to live in.
-	Neighbours: Neighbours, given the chance to show the different types of crimes that can be shown, can be reported. 
-	Anyone: this is a tool to show data, anyone can go on the website out of curiosity. Researchers can be involved on the website for their studies. 


### Use Cases
TODO: Describe each use case (at least one per team member).
    Give each use case a unique ID, e.g. UC1, UC2, ...
    Summarise these using the use-case template below.

| USE-CASE ID: UC101 (By: Seif Hassan), ... | USE-CASE NAME: Search Safe Neighborhood | 
| -------------------------------------- | ------------------- |
| **Description** | An international student trying to search for crime history in a specific neighborhood in Bristol to identify if it's safe to live live or not. |
| **Actors** | International Student |
| **Assumptions** | Pre-condition: Internet access available and basic knowledge of how to use a web application. Post-condition: The student identifies the neighborhood based on the provided crime data</td></tr>
| **Steps** | 1- User Action: The international student navigates to the website's home page.
              2- The system displays a search bar and an interactive map of Bristol.
              3- The student enters the name of a neighborhood or clicks on a specific area on the map.
              4- The system fetches and displays crime statistics (e.g., crime rate, most common crimes) for the selected area.
              5- The student reviews the data to assess whether his chosen neighborhood is safe for residence or not.
| **Variations** | The student may choose to filter the results by a specific time range |
| **Non-functional** | The system should load results in under 3 seconds. |
| **Issues** | The student may choose a time range that is out of our data set used. |


TODO: Your Use-Case diagram should include all use-cases.

![Insert your Use-Case Diagram Here](images/use-case.png)



## Software Requirements Specification
### Functional requirements
TODO: create a list of functional requirements. 
    e.g. "The system shall ..."
    Give each functional requirement a unique ID. e.g. FR1, FR2, ...
    Indicate which UC the requirement comes from.


### Non-Functional Requirements
TODO: Consider one or more [quality attributes](https://en.wikipedia.org/wiki/ISO/IEC_9126) to suggest a small number of non-functional requirements.
Give each non-functional requirement a unique ID. e.g. NFR1, NFR2, ...

Indicate which UC the requirement comes from.
