# EventsApp - Backend

## Project description

This repository contains the **Backend** of our sports event management platform, built with Laravel.  
It provides a **REST API** that handles all the data and business logic of the application.  

The backend works together with a separate **Frontend** developed in Angular, which consumes this API to provide the user interface.  

- **Backend (this repository):** Laravel REST API  
- **Frontend:** Angular application → [Frontend Repository](https://github.com/Dhoron22/Project_Event_FrontEnd.git)  

The goal of this website is to provide a service for the sports community to discover, promote, and manage sports events.

We have focused on local sports events, aiming to provide an intuitive interface for both organizers and users.

## Key Features

 - **Feature 1:** User registration and login
 - **Feature 2:** Events CRUD 
 - **Feature 3:** Users CRUD
 - **Feature 4:** Category CRUD
 - **Feature 5:** Country CRUD
 - **Feature 6:** State CRUD
 - **Feature 7:** Status CRUD
 - **Feature 8:** Roles CRUD
 - **Feature 9:** Registration CRUD
 - **Feature 10:** User authentication

---
## Technologies Used

### Backend (Folder: Project_Event_BackEnd)
 - **Languages:** PHP v8.2.12
 - **Frameworks:** Laravel v12.19.3
 - **Database:** MySQL
 - **Dependency manager:** Composer

---
## Local installation and execution
To run this project locally, follow the steps below:

### 1 Prerequisites
Make sure you have the following installed
 - **PHP:** v8.2.12
 - **composer:** v2.8.8
 - **Node.js:** v22.11.0
 - **MySQL:** 127.0.0.1
 - **Git:** The latest version

### 2 Clone the repository
Open your terminal and clone the repository in the same root folder:

# Clone the Backend repository (in a new terminal or by going back to the root folder)
cd .. # If you are in the frontend folder
git clone https://github.com/Dhoron22/Project_Event_BackEnd.git
cd Project_Event_BackEnd

## Development server

To start a local development server, run:

```bash
php artisan serve 
```
This project is built with Laravel. For full documentation, visit https://laravel.com/docs
