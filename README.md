# examples
Very Basic Examples of CRUD Operations

Hi I created a simple CRUD application.

Back-End: .NET Core 2.2 API Application. 
Database: MSSQL Server: using stored procedures and Dapper.
Front-end: Angular 8

Instructions: 

To run my application, you have to do the following: 

1. Run the .NET Core application, record the local port number. : Submission\Contacts_app_api


2. Open the Angular application: Submission\contacts_angular\contactsAngular\src\app\shared\contacts.service
	- Change myURL - (This variable contains the API base URL for the .NET core application)
        	- Change the port number to match the .NET Core Application port number.
3. Restore the Database onto your server: Submission\contacts.bak

4. In the NET Core application. 
	- Open the appsettings.json file and change the connection string as per point number 3

5. Run the apps, all should be in order.

