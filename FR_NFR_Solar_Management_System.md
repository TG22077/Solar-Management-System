Solar Management System - Software Requirements

** Functional Requirements **


a)	Login and User Management


1.	The system shall allow users to log in using a valid username and password.
2.	The system shall show different features depending on the user’s role (Admin / Customer).
3.	The system shall allow users to register or log in using Google account, Facebook account, or phone number (OTP verification).
4.	The system shall allow administrators to create, edit, or delete user accounts.


b)	Customer Management


5.	The system shall allow admin to create new customer profiles with contact and installation information.
6.	The system shall allow admin to update customer details when needed.
7.	The system shall allow admin to search and filter customers by name, phone, address, or customer ID.
8.	The system shall allow customers to view their energy usage summary.
9.	The system shall allow customers to view past installation and maintenance history including status (Pending / Completed) and detailed descriptions of each task.


c)	Energy Monitoring and Data Management


10.	The system shall allow admin to enter daily solar energy production for each customer.
11.	The system shall record energy consumption for each installation site including location and weather information.
12.	The system shall allow admin to record installation and maintenance tasks, including dates, technician name, status (Pending/Completed) and detailed task descriptions.
13.	The system shall generate daily, weekly, monthly and yearly energy performance reports.
14.	The system shall allow admin to export customer, energy, or service data in CSV or PDF formats.
15.	System shall allow admin to back up system data.
 


** Non-Functional Requirements **


a)	Performance

1.	The system should respond to user actions (login, viewing dashboard, generating reports) within 2 seconds under normal usage.
2.	Energy monitoring data updates and dashboard refreshes should occur within 5 seconds.



b)	Scalability

3.	The system must support at least 5,000 active customers and 100 concurrent admin logins without slowdowns.



c)	Availability / Reliability

4.	The system must be available at least 99.9% annually.
5.	Data should be preserved and remain accurate even during network interruptions or system crashes.



d)	Security

6.	including those linked to Google, Facebook, or phone number OTPs, must be securely encrypted and stored.
7.	Only authorized roles (Admin / Customer) can access their respective features.
8.	System shall implement session timeout after 15 minutes of inactivity.
9.	All changes to data (customer info, energy records, maintenance records) must be logged for audit purposes.



e)	Usability

10.	The interface shall allow users to perform key tasks within 3 clicks.
11.	Customers should be able to easily access their energy usage, services history and reports.
12.	Registration/login via Google, Facebook, or phone number should be simple, clear, and accessible.
13.	Location, weather info, energy data and maintenance/installation status and details should be displayed clearly in dashboards and reports.



f)	Maintainability

14.	Updates to software should not disrupt ongoing energy monitoring.



g)	Compatibility

15.	The system should work on major browsers (Chrome, Edge) and devices (desktop, tablet, mobile).






