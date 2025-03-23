# Implementation

## Introduction
TODO: Describe the system implemented (Describe the dataset. Are there any known issues? Describe any configuration data).

## Project Structure
TODO: Provide an outline of the project folder structure and the role of each file within it.
provide a table listing the number of jslint warnings/reports for each module.

```
└── 📁ISD Project (Bristol's Find a Crime)
    └── 📁.vscode
    └── about.html
    └── contact.html
    └── crime data.html
    └── index.html
    └── mapstyle.css
    └── report.html
    └── statistics.html
    └── styles.css
```

## Software Architecture
TODO: Describe the major components of your architecture. Are any particular architectural styles being used?

![Component Diagram](cmp.png)

## Bristol Open Data API
TODO: Document each query to Bristol Open Data


The class diagram represents the structure of the JSON response retrieved from the Open Data Bristol API named Street Crime Incidents, which is the dataset for crime data. The JSON class serves as the top-level container, holding multiple Feature objects, each representing a crime record. A Feature consists of an Attributes object, which stores key details such as crime id , crime category, location, date and outcome status. Additionally, each Feature includes a Geometry object containing the spatial coordinates (x and y) that define the crime location. The relationships between classes use composition, as Features, Attributes, and Geometry exist within the JSON response as nested structures. This diagram helps visualize how the data is structured and how different components are related within the API response.

![UML Class diagrams representing JSON query results](CD.png)


# User guide
TODO: Explain how each use-case works by providing step-by-step screenshots for each use-case. This should be based on a tested scenario.

![Screenshot 1 (Home Page)](s1.png)

![Screenshot 2 (Find a Crime Page)](s2.png)

![Screenshot 3 (Find a Crime Page)](s3.png)

![Screenshot 4  ](s4.png)

