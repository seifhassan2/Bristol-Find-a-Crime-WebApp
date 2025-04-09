# Testing

## Test Plan
For Use-cases 1 & 2 <br>
By: Seif Hassan

| Test Case ID | Test Tyoe | Description | Scenario |
| ---------- | -------------- | --------------- | --------- |
| TF1.1 | UAT | User can search for crime data by neighborhood | User enters a neighborhood name in the search bar <br> System displays crime data results for the selected area |
| TF1.2 | UAT | User can filter crime data by type | User searches for a crime type (e.g., burglary, theft) from the search bar <br> System shows results to display only that crime type |
| TF1.3 | UAT | User can load data from Bristol Open Data dataset | System fetches JSON data from the Bristol Open Data API <br> Crime info is displayed on the map and in tables |
| TF2.1 | UAT | User can submit new crime report via form | User fills and submits a report on the report a crime page <br> Confirmation message shown after submitting the form |
| TF2.2 | UAT | User can upload media with a report | User attaches a photo of the incident when reporting <br> System uploads and links it to the report |
| TNF1.1 | UAT | Load time for crime data under 3 seconds | User visits find a crime page <br> Crime info loads in < 3 seconds |
| TNF1.3 | UAT | Interface should be intuitive for new users | First-time user navigates both pages <br> Finds key features easily, without needing instructions |
| TNF2.3 | UAT | System should be user-friendly | Users complete core actions with minimal clicks <br> Form and map are responsive |
| TNF2.4 | UAT | Optional support feature provided | User finds an email for reporting bugs or help |

#

## Test Runs - Requirements Traceability Matrix 
For Use-cases 1 & 2 <br>
By: Seif Hassan

| Use-Case ID | Requirement ID | Software module | Test Case | Status |
| ---------- | -------------- | --------------- | --------- | ------- |
| UC1 | FR1.1 | crime data.html | TF1.1 | PASS |
| UC1 | FR1.2 | crime data.html | TF1.2 | PASS |
| UC1 | FR1.3 | crime data.html | TF1.3 | PASS |
| UC1 | FR1.4 | crime data.html | TF1.4 | PASS |
| UC1 | FR1.5 | crime data.html | TF1.5 | PASS |
| UC1 | FR1.6 | crime data.html | TF1.6 | FAIL |
| UC2 | FR2.1 | report.html | TF2.1 | PASS |
| UC2 | FR2.2 | report.html | TF2.2 | PASS |
| UC2 | FR2.3 | report.html | TF2.3 | FAIL |
| UC2 | FR2.4 | report.html | TF2.4 | FAIL |
| UC1 | NFR1.1 | report.html | TNF1.1 | PASS |
| UC1 | NFR1.2 | report.html | TNF1.2 | FAIL |
| UC1 | NFR1.3 | report.html | TNF1.3 | PASS |
| UC1 | NFR1.4 | report.html | TNF1.4 | PASS |
| UC2 | NFR2.1 | report.html | TNF2.1 | PASS |
| UC2 | NFR2.2 | report.html | TNF2.2 | PASS |
| UC2 | NFR2.3 | report.html | TNF2.3 | PASS |
| UC2 | NFR2.4 | report.html | TNF2.4 | PASS |
| UC2 | NFR2.5 | report.html | TNF2.5 | FAIL |

