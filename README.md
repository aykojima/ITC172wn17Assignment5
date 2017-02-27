# ITC172wn17Assignment5
WCF Service

For this assignment we will create a WCF (Windows Communication Foundation) service.
We will use Data Entities for the Model. You will need the tables Person, PersonAddress, Contact, GrantRequest and Grant review and you will need the sored procedures usp_Login and usp_Register.
The service should have all the methods necessary to all a new user to register, login, apply for a grant, and see all the grants they have applied for and their status. Specifically you will need methods for
Logging in (this will use the login stored procedure and you will need to get the PersonKey)
Registering (this will use the Register stored procedure)
Requesting a grant (you should also add the Grant to the GrantReview table with review status = "pending"
Viewing grants (filtered by PersonKey)
Test each method to make sure it works
