# Login And Registration form

## Table of contents:-

- [Introduction](https://github.com/manikandaraj-T-N/Login/blob/main/README.md#introduction)
- [Technologies Used](https://github.com/manikandaraj-T-N/Login/blob/main/README.md#technologies-used-)
- [Prerequisites](https://github.com/manikandaraj-T-N/Login/blob/main/README.md#prerequisites-)
- [Implementation steps](https://github.com/manikandaraj-T-N/Login/blob/main/README.md#implementation-steps)
- [Installation steps](https://github.com/manikandaraj-T-N/Login/blob/main/README.md#installation-steps-)
- [Output of project](https://github.com/manikandaraj-T-N/Login/blob/main/README.md#output-of-project-)
- [Features](https://github.com/manikandaraj-T-N/Login/blob/main/README.md#features-)

## Introduction:
This project demonstrates the implementation of Login and Registration functionalities using JSP, Servlet and MySQL. The project includes a Registration form where users can register themselves by providing their details like name, email, password, etc. Once the user is registered, he/she can use the Login page to enter the credentials and log in to the system.

## Technologies used:-

#### Back-end :
- MySQL Database 
- JDBC (Java Database Connectivity)
- Servlet
- JSP (JavaServer Pages)

#### Front-end :
- HTML 
- CSS
- JavaScript

## Prerequisites:-

- Java Development Kit (JDK) version 8 or above
- Apache Tomcat version 8 or above
- Eclipse IDE (or any other IDE of your choice)
- MySQL database

## Implementation Steps
- Create a MySQL Database and Tables
- Develop the Registration Form using JSP and HTML
- Develop a Servlet to Handle the Registration Form Submission
- Add Server-Side Validation to the Registration Form
- Develop the Login Form using JSP and HTML
- Develop a Servlet to Handle the Login Form Submission
- Add Server-Side Validation to the Login Form
- Implement the Forgot Password Functionality
- Develop a Password Reset Form and Servlet
- Add Server-Side Validation to the Password Reset Form
- Testing

## Installation steps:-

- Clone the repository to your local machine.
- Import the project into Eclipse IDE.
- Create a database in MySQL and execute the SQL script provided in the 'database' folder to create the necessary tables.
- Update the database connection details in the 'DBUtil.java' file.
- Build and run the project on Apache Tomcat server.
- Access the application using the URL 'http://localhost:8080/login-registration'.

## Output of Project:-
#### Registration Page
![Login-Registrationpage](https://user-images.githubusercontent.com/93505267/234291593-066800a0-12a7-4f0c-bb35-1cdef2734bc5.png)


#### Login Page
![Login-Loginpage](https://user-images.githubusercontent.com/93505267/234291526-6d2df10b-68e5-47b4-ae55-25000f9afacc.png)


#### ForgotPassword page

##### Note: When you click on Forgot Password on Login page, It will shows below page to enter the your validated email to send the otp.

![Login-forgotpassword](https://user-images.githubusercontent.com/93505267/234458670-3cc90d28-52d8-476e-8ccf-7ddd24d96d66.png)

##### After enter email addresss, click on Get New password and it will redirect to below page to enter the otp(otp is sent to entered email address)
![Login-enterotp](https://user-images.githubusercontent.com/93505267/234458467-12133caf-414a-4bee-853c-d235b6efb4f9.png)


#### OTP Validation page

##### When you click Reset password button on above page, it will validate the otp.
##### Note: Below page shows wrong otp, when you entered wrong otp.

![Login-validateotp](https://user-images.githubusercontent.com/93505267/234459006-fccff8c6-1fb9-484b-9b00-9f6e53465fe4.png)


#### New Password

##### When we entered correct otp, it will redirect to below page

![Login-Enternewpassword](https://user-images.githubusercontent.com/93505267/234458504-a72823ca-e508-4fd6-b3b8-5758792d5a12.png)


#### Reset Successfully

##### After giving new password, click on Reset password and  it will shows alert as Password reset successfuly

![Login-resetsuccessfull](https://user-images.githubusercontent.com/93505267/234458852-24ec6948-a293-4b56-9b60-64c4b0532122.png)


#### Final Output(Log in to system)

![Login-finaloutput](https://user-images.githubusercontent.com/93505267/234458441-2d3e66e6-93b0-4bb6-9cac-2aacf2f30a11.png)

## Features:-

- User registration with client-side and server-side validation.
- User login with session management.
- Forgot password functionality with email verification.
- Password reset functionality.
-  hashing for secure storage.
- Responsive UI design using Bootstrap.

## 🔗 Link for contact:-

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manikandaraj-t-n-834189173/)
