# Blood Donation Project

This project serves as a hub for individuals in need of blood donors during emergencies and for those who wish to help others. The application features user registration, profile management, and blood donation requests, all organized into three distinct apps: `account`, `blood`, and `admin`.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Apps Overview](#apps-overview)
  - [Account App](#account-app)
  - [Blood App](#blood-app)
  - [Admin App](#admin-app)
- [Contributing](#contributing)

## Features
- User registration and login with custom user model.
- Profile creation and management, including blood donation eligibility checks.
- CRUD operations for blood donation requests.
- Admin dashboard for managing users and donation requests.
- JavaScript integration for dynamic form fields based on user selections.
- Bootstrap for responsive design.

## Requirements
1. **User Registration**
   - Implement a custom user model with a registration function (function-based view).
  
2. **User Login**
   - Check for a corresponding profile upon user login. If a profile exists, redirect to the homepage; otherwise, redirect to a profile creation form.

3. **Profile Page**
   - Create views for viewing and updating user profiles, with restrictions on changing blood type and availability based on donation history.

4. **Blood Donation CRUD**
   - Model for blood donation requests.
   - Class-based views for creating, updating, deleting, listing, and viewing blood donation requests.

5. **Admin Dashboard**
   - Authentication and authorization for admin access.
   - Functionality for admins to manage users and blood donation requests.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bloodbank.git
   cd bloodbank
