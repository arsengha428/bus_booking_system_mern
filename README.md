# Online Bus Booking System
This houses the code for the Online Bus Reservation System, a robust platform designed for seamless ticket booking and management. Created with the aim of elevating the convenience of bus travel, it enables users to reserve, edit, and cancel their bus tickets online, from the comfort of their homes. The key features include real-time seat availability checking, secure payment gateway, and user-friendly interface. Here, administrators can efficiently monitor trip schedules, manage routes, and handle pricing. The back-end programming involves advanced algorithms ensuring optimized seat allocation and fare calculation. The code is open source, aiming at inspiring enthusiasts to learn, contribute, and build further on this project. To get this system up and running, follow the installation guidelines provided in the repository.

## Bus Booking System (Web version) (Next.JS): 
### Step 1: Setup Environment Variables
Create a file named ".env.local" in your project root directory (the same level as "package.json"). Copy and paste the following content in that file:
```
MONGO_URI = "path to mongodb url"
userEmail = "your email"
userPass = "your password"
JWT_SECRET = "your secret here"
```
### Step 2: Install Dependencies
Ensure you have Node.js and npm installed in your system. Afterwards, navigate to your project folder in the terminal and run the following command to install the necessary dependencies:
* #### yarn
* #### yarn server
* #### go to client repo
* #### yarn
* #### yarn dev

## CRM
### Setup Environment Variables
* #### clone the entire repo
* #### go to server repo
* #### make environment file with the following keys' values:
```
MONGO_URI = "path to mongodb url"
userEmail = "your email"
userPass = "your password"
JWT_SECRET = "your secret here"
```
* #### yarn
* #### yarn server
* #### go to CRM repo
* #### make environment file with the following keys' values: 
```
REACT_APP_API_URL = http://localhost:8525/api
REACT_APP_SERVER_ROUTE = http://localhost:8525
REACT_APP_JWT_SECRET = "your secret here"
```
* #### yarn
* #### yarn start

## Bus Booking System (Mobile version)
* #### clone the entire repo
* #### go to app repo
* #### yarn
* #### having expo installed in your system, expo start
