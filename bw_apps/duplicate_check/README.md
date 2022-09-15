# Usecase
In this tutorial, we are demonstrating the below listed usecases.

 - How to load the data from a CSV file
 - Connecting to a locally hosted database
 - Identifying the Duplicates with DATA available into DB table; Comparing the data to ensure only unique values get processed
 - Connecting to Salesforce
 - Updating the salesforce Order object with unique order details.
 
We are demonstrating the same usecase using two different integration patterns. 
1. **APILed Integration pattern** <br />
 Using a microservices architecture to divide a functionality into smaller services and those services can be used individually. Ex. Creating Object in Salesforce, or findong duplicates for incoming data against db, etc. <br /><br /> ![image](https://user-images.githubusercontent.com/38240734/190411363-53ff5c24-530b-42f3-8a0e-7939fffcb4af.png)


2. **Traditional Integration approach** <br />
One flow contains all the business logic (the cluttered way to doing it). <br /> <br /> ![image](https://user-images.githubusercontent.com/38240734/190411227-307d8d2b-3555-4a11-8083-20e2bf49d9b6.png)

 
## HowTo Run?
  - Import the application
  - Open Module Descriptor > Module Properties
  - Update the csv file location (according to your filesystem), Update the DB and salesforce credentials, etc
  - Validate the application for Errors.
  - Click Run > Debug Configuration > select all the processes
  - Debug

## Reference
