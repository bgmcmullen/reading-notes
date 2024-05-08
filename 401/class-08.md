# Class 06 Reading Notes:


### What is Role-Based Access Control (RBAC) and why do we care? 
Role-based access control is a way to give users of a site only access to specific functions based on what their role is. This is important to make sure that important changes on a website can only be done by those with the proper authority.
### Describe a Role/Permission hierarchy that you might implement using RBAC. 
Manager: create, read, update, delete\
Employee: read, update\ 
Guest: read
### What approach might you take to implement RBAC?
First, identify roles and what permissions each should have, then assign the roles to the users, and finally run tests to make sure the system is working and no one has access to permissions they should not.
### If Authentication is “you are who you say you are,” what is Authorization?
“Do you have permission”
### Name three primary rules defined for RBAC.
Role assignment, Role authorization, Permission authorization
### Describe RBAC to a non-technical friend.
When you log in to the New York Times website, RBAC is what gives you the option to comment, which a non-member would not have, but you can’t upload your own article unless you write for the Times. 
### What Are access rights Associated with? The User? or The Role? Explain.
Access rights are associated with the role, and a user is assigned a role based on their identity.
### Access Rights, or Authorization, are activated after a user successfully does what?
Logs in and is authenticated
### Explain how RBAC might benefit a business. 
New employees can immediately have access to necessary privileges based on their role. Sensitive information can only be available to those who need it.


