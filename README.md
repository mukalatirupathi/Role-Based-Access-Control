# Role-Based Access Control (RBAC) System :

This project is a Role-Based Access Control (RBAC) system built with React, providing a way to manage users and permissions based on their assigned roles. The application supports the following roles:

Admin
User

# Features:

**Login System**

Users and Admins can log in with a valid username and password.
Credentials for Admin:

Username: admin
Password: admin@2024

**Dashboard**
After login, users and admins are redirected to their respective dashboards.
**User Dashboard:**
Displays the username and role.
Shows the permissions available for the logged-in user:

YOUR ROLE PERMISSIONS

Permission     Access
Read Access    Granted
Write Access   Denied
Delete Access  Denied

Users cannot add new users (to be implemented).

**Admin Dashboard:**

Displays the username and role.
Shows the permissions available for the admin:

YOUR ROLE PERMISSIONS

Permission     Access
Read Access    Granted
Write Access   Granted
Delete Access  Granted

Admins can:

Add new users on the User Management page.
Update permissions for Users/Admins/Managers via the "Update Permission" button.
Manage roles and permissions via the "Role Management" button in the header.

**User Management**

Users and Admins can navigate to the User Management Page.
Admins can:
Add new users using the "Add User" button.
Update roles and permissions for existing users.

**Role Management**

Admins can access the Role Management Page through the "Role Management" button in the header.
The page displays role-based access permissions and provides an "Edit" button to modify access permissions for any role.

**Logout**

Users and Admins can log out using the Logout button, which redirects them back to the login page.

**Technologies Used**

Frontend: ReactJS
Styling: CSS
State Management: UseState Hook
Routing: React Router


**How to Run the Project**

Prerequisites

Node.js (v16+ recommended)
npm or yarn package manager

**Steps**

Clone the repository:

git clone <repository-url>
cd <repository-folder>

Install dependencies:

npm install

Start the development server:

npm start

Open the application in your browser at http://localhost:3000.

**Remaining Tasks**

Implement restricted access for users:
Users should not be allowed to add new users.
Add functionality for the Manager role (if required).
Perform additional testing and validation.

**Future Enhancements**

Enhance UI/UX for a more intuitive experience.
Add password encryption for secure login.
Implement a backend service for storing user data and permissions.
Extend support for more roles and permissions.