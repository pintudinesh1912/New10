# New10 test automation

### Best Buy API
Rest API automation framework implemented using Postman and Newman.

### Prerequisite:
List of all the software and tools required for developing and executing automation framework.
npm (version 5.6.0) Postman (version 7.9.0) Newman (version 4.5.5)

### Automation Scripts Execution:
To execute the test script please follow below steps:

1.Download npm from website "https://nodejs.org/en/download/"

2.Install Postman from "https://www.getpostman.com/downloads/"

3.Install Newman inside node modules folder of npm from command line using command "npm install newman –global"

4.Install newman html reporter for better reporting purposes inside node modules folder of npm from command line using command "npm install -g newman-reporter-htmlextra"

5.Download the BestBuyAPI-Services.postman_collection.json file

6.Open command line in the directory where this file is stored and run below command: "newman run BestBuyAPI-Services.postman_collection.json -r htmlextra --reporter-htmlextra-darkTheme --reporter-htmlextra-title “New10””

7.Once the file has run, report will be generated inside a newman folder that would be created in the directory where the json file is saved

### Automation Coverage/Test Scenarios:
1. Scenarios for GET services
2. Scenarios for GET services with ID
3. Scenarios for POST services
4. Scenarios for PATCH services
5. Scenarios for DELETE services

### Automation Execution Status:
Newman report is available in the repository "BestBuyAPI-Services-2019-11-24-15-42-53-918-0.html" which covers 16 requests with 56 assertions out of which all have PASSED
