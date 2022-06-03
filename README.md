# Expense-Reimbursement-System 

## Project Description
The Expense Reimbursement System manages the process of reimbursing employees for expenses incurred. 

## Technologies Used
- Javalin, version 4.1.1
- Java, version 1.8.0
- slf4j version 1.7.32
- Gradle
- Javascript
- HTML
- CSS
- React

## Features

- Employees are given the option to be registered into the system with a chosen unique username and a(n) auto generated account Id that will be associated with the account. 
- An employee will be able to login to the account with the corresponding username and password, and submit a reimbursement request for later approval .
- The employee may display previous request that have been resolved and filter the result by type of reimbursement. 
- Pending requests may also be viewed and its results can also be filtered by type. 

- Managers are given the same functionality as employees, in additions to added features
- View all pending reimbursement requests made by the employee, and filter the request by type, author, and reimbursement id (as indvidual filters or cumulative)
- View all resolved requests and filter the results by reimbursement type, id, and author. 
- Managers may choose to deny or approve pending requests (by clicking on react-icons) after filtering the results based on type, author, or reimbursement id.

- Employees and Managers are able to easily navigate through the page with the nav bar present on each screen

To-do List
- Implement password enscription
- Filter results by data within a given range
- Style user interfaces according to a consistent layout for better user experience
- Use local storage to have data persistent after refreshing the page

## Getting Started
1. Clone repository into the a working directory with the following command:
  git clone https://github.com/robpduo/Expense-Reimbursement-System.git

2. Run the Javalin server in the root directory under app/src/main/java/com.revature/driver.java

3. Run the React front-end components by changing directory into ers-frontend folder from the root director:
  cd ers-frontend/
  npm start

4. Setup the database using the script file provided in the resource folder located in app/src/main/resources/ers script.sql

## Usage
1. Register a new user as an employee
![image](https://user-images.githubusercontent.com/101683611/171868865-3b5eee96-ece5-4897-b5ae-7c5f60882c6b.png)

2. Navigate to 

  
