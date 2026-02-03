ASP.NET MVC Authentication Project

Overview
This project is built with ASP.NET MVC.
It has a system for User and Admin registration and login.
It uses JWT Token for authentication and Session for storing user info.
There are separate dashboards for Admin and User.

Features
Register new users with name, email, password, gender, and interests.

Login for both Admin and User.

JWT Token is created after login.

Show different dashboard pages based on role:

Admin Dashboard

User Dashboard

Logout clears the session and goes back to login page.

Technologies
ASP.NET MVC 5

Entity Framework

SQL Server

C#

HTML + CSS

Project Structure
Code
Task/
 ├── Controllers/
 │    └── RegisterController.cs
 ├── Models/
 │    └── Register.cs
 │    └── Admin.cs
 ├── Services/
 │    └── TokenServices.cs
 ├── Views/
 │    ├── Register/
 │    │    ├── Register.cshtml
 │    │    ├── Login.cshtml
 │    │    ├── UserDashboard.cshtml
 │    │    └── AdminDashboard.cshtml
 └── README.md
