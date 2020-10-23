#Build a link shortener with a twist using Azure SQL Database

Azure SQL Database is an incredibly powerful data storage technology provided as part of the Microsoft Azure cloud. It provides an extraordinary level of modern SQL capability that can be harnessed quickly and seamlessly. It’s a very cost-effective way to build out cloud native applications using familiar technologies. In this project i have provision an Azure SQL Database and a serverless function app to create a basic link shortener service in minutes all without leaving the Azure portal! Then i have expand on that to add a surprise twist to the service.

01_sqlcreate.sql: SQL to create the schema and insert a test record, 
02_azurefunction_initial.js: Azure Function Node.js code with initial SQL connection, 
03_azurefunction_connectionpooling.js: Azure Function Node.js code with initial SQL connection, 
04_azurefunction_appsetting.js: Azure Function Node.js code that adds connection pooling, 
05_azurefunction_realquery.js: Azure Function Node.js code that adds the real SQL query, 
06_azurefunction_final.js: Azure Function Node.js code with final code, 
07_azurefunction_luckydip.js: Azure Function Node.js code with lucky dip function code, 
08_addmorelinks.sql: SQL to insert a few extra links,
