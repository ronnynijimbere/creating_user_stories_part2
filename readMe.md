An application that a store owner can use to keep track of inventory

Inventory

User (Customer)
1. Login/Logout out Access with Authentication (Google, Facebook, LocalStrategy)
2. Redirect to online shopping only

User (Employee)
1. Login/Logout out Access with Authentication (Google, Facebook, LocalStrategy)
2. Redirect to online shopping and inventory
3. Check Current Inventory (store stock count)
4. Able to view Inbound and outbound

User (Admin/Owner/Manager)
1. Login/Logout out Access with Authentication (Google, Facebook, LocalStrategy)
2. Redirect to online shopping and inventory
3. Check Current Inventory (store stock count)
4. Able to view Inbound and outbound
5. Able to purchase orders for store
6. Able to set user access for both Customer and Employee

A. Software requirements documentation

System Architecture
Describe the web stack that you plan to use for developing the application?

This project will aided with the Use of the Mern Stack
1.MongoDB: Store users credentials with their Authentications;
2.Express.js to be used to build server side software;
3.Next.js which is a React Framework that allows us to build web appls using JavaScript and React more quickly for Our Front-End;
4.Node.js which is a runtime environment that can run javascript files without a browser on the web server,
Javascript can be used on the server side with Nodejs.

How will you deploy the app? Why?
This is a learning exercise for a Fictious store: it will be doployed on github and Heroku

What tools have you used for styling your app? What motivated this choice?
1.Bootstrap and Style jsx will be used. However this is subject to change during the course
of the project depending on how the User Interface (UI) will turn out,

B. System Requirements Specification

Describe exactly how your application will work?

When the Owner/Manager logs in the App, they need to focus mainly on the inventory,
This inventory must be able to the Owner/Manager know which are the fast and slow selling items;
A daily, weekly and monthly report can be generated to assist the owner/manager make business decisions
 
Who will use your application?
Business that have barcoded items. Items that do have barcodes, Admin can generate them when the inventory created.


How will they benefit from using it?. 
As mentioned , this is guide Owner/Manager to make sound business decisions

Also explain what other software there is that currently does
something similar to what you are planning and how your software will be
different (will it be simpler to use, cheaper, improve certain functionality?
etc);

There is Warehouse Management System (WMS) called Optima which I can Accross Working In the Logistics Industry which,
is similar to what i want to achieve, However with the inventory i want to create, the items need to have costs values,
so that the owner/manager can generate a profit/loss report. Also adding the delivery costs and salaries for employees
could also assist with the running of the business (Although this might be necessary).

Functional Requirements

What the System should

1.Log in and out
2.Upload inventory Reports,
3. Make changes to items price change (Owner/Manager) only.

Expected Users
Students with Smartphones, Laptops and personal computers.

D. Non-Functional Requirements

Usability: Free Training to be provided to user(employees) and owner/manager on how to use the App

Reliability and Performance: to help ensure that system functions as expected,
system updates and routine maintance will done daily, weekly at a time agreed to by the specifically when there is less activity
(early hours of the morning 12am-3am) or at a time agreed to by the owner/manager.

Security: Secured Authentication will be through these account gmail, facebook, github and twitter,
they will be able to sign up or log in. 
