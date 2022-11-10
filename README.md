# cloud-resume-azure
My resume, hosted on Azure following the ACG resume project video

## Steps taken

 The frontend folder contains the html and other website contents like main.js which is the code that will act as the visitor counter

 Created an Azure Cosmos NoSQL Database account and container to hold the visitor counter number


 Created an HTTP Trigger Azure function, and used Azure Cosmos DB bindings to bind the database to the function in the cloud. Now, the visitor counter is fully stored and running in Azure