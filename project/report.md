# Deployement Of Database in Multiple Cloud

Balakrishna Katuru(Bala) - **[fa19-516-141](https://github.com/cloudmesh-community/fa19-516-141)**.<br/>

## Objective 
Deploying the Database in multiple clouds.

## Facts and comparisions about top could service providers
This section discuss about the details of various cloud service models, public cloud service market share of major service providers. And also what are the challenges the customers expereinced while using cloud services. 

## Types of Cloud – Services Models

![Image](https://www.devteam.space/wp-content/uploads/2017/07/Cloud-Models.jpg)

## Enterprice Public Cloud Adaption
Look at the major public cloud providers stake.
![Image](https://zdnet1.cbsistatic.com/hub/i/r/2018/02/09/2b5981e1-19e6-4e79-986c-44d849a2235a/resize/770xauto/74c392ed6832b01e638db63639c3295c/stacking-up-cloud-vendors-2018-right-scale-1.png)

 Top four Cloud service providers Scorecard in 2018.
![Image](https://zdnet2.cbsistatic.com/hub/i/r/2018/02/09/b6fed299-809f-43fc-a732-f1343ec2b8d9/resize/770xauto/98f060c985c6b39b00822a62e1d3c15a/aws-vs-azure-vs-google-vs-ibm.png)

 The challenges while using the Cloud services are given below
![Image](https://zdnet4.cbsistatic.com/hub/i/2019/01/23/e19ceee2-17bd-4a4f-9249-82613ec7a428/20a459a33fd6e9176e29346fb0d78a5f/kentik-report-2019a.png)

## Project Synapsis 
- Can be considered cloud storage(Example: Create a Bucket in case of Google)
     to deploy the Database. 
- Adapt a cloud based storage service using REST service & APIs.
- The Database will be deployed in multiple clouds using the appropriate storage service.
- Use an abstract API to deploy the Database independent of the underlying infrastructure.

## Technologies
* Python 
* Cloudmesh 
* AWS 
* API / Rest

## Overview
  This application will be developed using AWS SQL databaseas back end and Python Flask to create front end UI.
 
  Backend: My SQL server database will be created on AWS. And then a table to be created to store the data Ex: Employee Name, Employee ID, Department, Salary, Phone, Email.
  
  Frontend: Frontend will have basic controlsto input teh data like employee details. With user interaction, CRUD operations will be performed. Display all records, add new record, update existing record and delete the existing record.
 
 Modules: Table, flask, mysql.
 
## Implementation and Deployement steps
1) Creation of cloud accounts
2) Creating directories:
3) Creating Flask Module: Create app.py script to import the flask module.
4) Creating Database Configuration: Create db_config.py Python script to setup the MySQL database configurations to connect the database. 
5) Creating Main Script: Create main.py script, that will define all URIs or Action paths to perform CRUD operations with user interation.
6) Implementing REST End Points: 

## Test Scenarios
1) When execute the python main.py, the server will start on default port 5000.
2) Success massage after insert data in to table. And also teh message after successful Update/delete operation.
3)
4)

## Participants 
Bala

## References

1. <https://blog.rapidapi.com/how-to-use-an-api/>
2. <https://www.devteam.space/blog/top-10-cloud-computing-services-providers/>
3. <https://www.zdnet.com/article/top-cloud-providers-2018-how-aws-microsoft-google-ibm-oracle-alibaba-stack-up/>
4. 
