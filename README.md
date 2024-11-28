# VRV Security’s Backend Developer Intern Assignment

# Role-Based Access Control (RBAC)

## Overview

This is a web application developed using the MERN stack to demonstrate **Role-Based Access Control (RBAC)**. It is designed for a security service company with three user roles: **Guard**, **Manager**, and **Authority**. Each role has different access permissions to the available services.

## Live Demo

You can access the live version of the application here:  
[**Live Demo**](https://vrv-assignment-swe.onrender.com/)

## Features

- **Authentication**: JWT (JSON Web Tokens) are used for authenticating users.
- **Authorization**: Different roles have access to different sets of services.
- **Roles**:
  - **Guard**: Limited access to services like CCTV surveillance.
  - **Manager**: Extended access to services such as guards deployment and attendance records.
  - **Authority**: Full access to all services, including active units and more.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Password Hashing**: bcrypt.js

## Setup & Installation

### Clone the repository and install required dependencies in client & server.
