# WatsonDiscovery_AgentAssist_IBM Watson Discovery for Salesforce
This repo illustrates how agents can utilize Watson APIs for quicker resolution of customer service tickets

In this repo we will illustrate the following usecase:

- Live Agent - Agent Assist usecase incorporating Watson Assistant with Watson Discovery

## Setup
- Hint! Chatter must be installed before you can install IBM Watson Discovery for Salesforce
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/installchatter.png)
- Hint! Cannot add custom components to lightning app builder unless a domain is deployed to users, use QuickFind to go to "my domains"
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/domain.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/domain2.png)

### Part 1 - Salesforce Setup & ServiceCloud Setup

- Obtain a Salesforce instance with Administrator access and log in

### Part 2 - Download & Install IBM Watson Discovery for Salesforce from the Salesforce AppExchange 
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/installpage.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/installprompt1.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/Installconfirm.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/installWDSforSF.png)

### Part 2a - Connect to IBM Cloud account & create or connect to an existing Watson Discovery Instance
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/installprocess.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/connecttowatson.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/connecttowds1.png)

### Part 3 - Add Data to Watson
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/adddatatowatson.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/adddatatowatson2.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/adddatatowatson3.png)

### Part 4 - Configure & Personalize Your App In Lightning App Builder
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/configure.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/configure2.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/configure3.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/configure4.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/configure5.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/configure6.png)

### Part 5 - Navigate to case, then edit page & use Lightning App Builder to add custom Watson Discovery component to case record page template for agent
- Use Left Upper Dots to to search apps and choose ServiceApp
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/1_servicecloud.png)
- Click on cases, gear and edit page
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/2_casesandeditpage.png)
- Use lightning app builder to add Watson Discovery component to case record template
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/customcomponent1.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/3_lightningappbuilder_before.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/4_lightningappbuilder_after.png)
- Save then Activate to deploy to users
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/5_saveandactivatetodeploytousers.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/6_deploytoorg.png)
- Choose assign to org default(if you wish) or other options
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/7_assigntoorg.png)
- Choose form factor
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/8_assignformfactor.png)
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/9_save.png)

### Part 6 - Verify Watson Discovery shows on cases
![test](https://github.com/bmguillo/SalesForceServiceCloud_AgentAssist_IBMWatsonDiscoveryforSalesforce/blob/master/img/DiscoveryDeployed.png)

]


Resources:
- Download/Install Page for IBM WDS for Salesforce:https://appexchange.salesforce.com/appxListingDetail?listingId=a0N3A00000EtDziUAF&modal=where_to_install_package
- Blog on IBM WDS for SF: https://www.ibm.com/blogs/watson/2018/09/introducing-watson-discovery-for-salesforce-an-ai-powered-insight-engine-for-crm/


