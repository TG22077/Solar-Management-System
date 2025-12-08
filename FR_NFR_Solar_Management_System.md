Solar Management System - Software Requirements

Functional Requirements
a) Login & User Management
1. The system shall allow users to log in using a valid username and password.
2. The system shall show different features depending on the user’s role (Admin / Customer).
3. The system shall allow administrators to create, edit, or delete user accounts.

b) Customer Management
4. The system shall allow admin to create new customer profiles with contact and installation information.
5. The system shall allow admin to update customer details when needed.
6. The system shall allow admin to search and filter customers by name, phone, address, or customer ID.
7. The system shall allow customers to view their energy usage summary
8. The system shall allow customers to view past installation and maintenance history.

c) Energy Monitoring & Data Management
9. The system shall allow admin to enter daily solar energy production for each customer.
10. The system shall record energy consumption for each installation site.
11. The system shall allow admin to record maintenance tasks, including dates and location.
12. The system shall generate daily, weekly, monthly and yearly energy performance reports.
13. The system shall allow admin to export customer, energy, or service data in CSV or PDF formats.
14. System shall allow admin to back up system data.
 
Non-Functional Requirements
a) Performance
1. The system should respond to user actions (login, viewing dashboard, generating reports) within 2 seconds under normal usage.
2. Energy monitoring data updates and dashboard refreshes should occur within 5 seconds.

b) Scalability
3. The system must support at least 5,000 active customers and 100 concurrent admin logins without slowdowns.

c) Availability / Reliability
4. The system must be available at least 99.9% annually.
5. Data should be preserved and remain accurate even during network interruptions or system crashes.

d) Security
6. User credentials must be encrypted and stored securely.
7. Only authorized roles (Admin / Customer) can access their respective features.
8. System shall implement session timeout after 15 minutes of inactivity.
9. All changes to data (customer info, energy records) must be logged for audit purposes.

e) Usability
10. The interface shall allow users to perform key tasks within 3 clicks.
11. Customers should be able to easily access their energy usage, services history and reports.

f) Maintainability
12. Updates to software should not disrupt ongoing customer billing or energy monitoring.

g) Compatibility
13. The system should work on major browsers (Chrome, Edge) and devices (desktop, tablet, mobile).
