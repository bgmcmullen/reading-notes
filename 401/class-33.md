# Class 33 Reading Notes:

## What is Role Based Access Control (RBAC)?

### 1. What is Role Based Access Control (RBAC)?
Role-based access control is a way of protecting data by restricting access based on the user's role.

### 2. Share an example of RBAC including all possible CRUD operations and correlating roles.
Admin: Has full access to all CRUD operations on users.
Manager: Can create, read, update, and delete users, but cannot delete other managers.
Employee: Can only read information about users but cannot perform any CRUD operations.
### 3. What are the Benefits of RBAC?
RBAC helps keep data safe by minimizing the number of people who have access to sensitive information.

##Compare and Contrast the following two Libraries and the following questions. Yes, they are similarly named.

react-cookie library
react-cookies component

## 1. Describe some react-cookie features.
React-cookie allows you to set a cookie with a name, value, and a number of options including the path, the expiration date, the domain, and whether it is secure.

## 2. Describe some react-cookies features.
React-cookies offers utility functions for working with cookies, such as getCookie, setCookie, and removeCookie. These functions are typically used as standalone utilities rather than being integrated into React component state.

## 3. Which library would you prefer? Why?
I am tempted to say that I prefer react-cookie as it seems to have better documentation.








