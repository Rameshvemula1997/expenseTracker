# **FINANCE TRACKER APPLICATION - BACK-END PROJECT DOCUMENTATION** #

### **_Project Overview_** ###
This application can be your reliable companion for managing and tracking your financial transactions effortlessly. This application is designed to provide a seamless experience for users to record, categorize, and analyze their expenses and incomes, helping them gain insights into their spending habits and savings.

### **_Dependencies_** ###
* **Node.js :** The project is built by using Node.js for all the server side developments.
* **Express.js :** All the API's are built using express.js.
* **MongoDB :** As a NoSQL database, it is very efficient for storing and managing data.  
* **JWT Authentication :** JSON Web Token (JWT) authentication system is used to ensure secure data sessions.
* **DOTNEV :** All the configuration variables, passwords etc are isolated using dotenv library. 
* **Crypto :** Crypto is being used for encrypting the passwords for storing it to the database.
* **RESTAPI :** RESTAPI architecture is followed throughout the application.

### **_Scope And Objectives_** ###
* #### **Scope :-** ####
  
  * The application aims to track and categorize all the incomes and expenditures providing users with a clear overview  of their spending and savings.

  * It includes features for manual entry, automatic categorization, and analysis of expenses and incomes. 

* #### **Objectives :-** #### 
  
  * User can create, list, search and delete their own set of categories and transactions.
  * Enable users to track their income and expense respectively.
  * Support users in planning for future financial goals.
  * Maintain the security and privacy for each users information.

### **_Features_** ###
  
  * #### **Efficient Database -** ####
    * The database used in this application - **"MONGODB"** is one of the best and trending nosql databases in today's world.
  
  * #### **RESTAPI** ####
    * All the API endpoints are in complete sync with the RESTApi method.
  
  * #### **Encrypting Password** ####
    * The password given by the user is encrypted before storing it to the database, establishing a very secure environment for the  user.
  
  * #### **Login Token** ####
    * The user is given a token at the time of login by which the user can login without sharing the password each time.
  
  * #### **Paginated Response** ###
    * All of the response sent from the server is properly paginated and also a default pagination is set.
  
  * #### **Invite-Only Registration System** ####
    * For a user to register, the user will be needing the token of the **"ADMIN"** user, failing to which the user cannot register to the application.
