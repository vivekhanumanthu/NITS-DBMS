# NITS-DBMS
![Uploading image.png…]()


College Database Management System (MERN Stack)
Welcome to the College Database Management System! This system is built using the MERN (MongoDB, Express.js, React, Node.js) stack to manage data for admins, students, and faculty.

Installation
Prerequisites
Node.js and npm installed
MongoDB installed and running
Setup Instructions
Clone the repository:

bash
Copy code
git clone <repository_url>
cd college-database-management-system
Install server dependencies:

bash
Copy code
cd server
npm install
Set up environment variables:

Create a .env file in the /server directory with the following variables:

plaintext
Copy code
MONGODB_URI=<Your_MongoDB_Connection_String>
PORT=<Your_Server_Port>
Seed the initial admin credentials:

Open MongoDB Compass and connect to your MongoDB server. Insert the following document into the admins collection to create the initial admin:

json
Copy code
{
  "username": "admin",
  "password": "<Your_Admin_Password>"
}
Start the server:

bash
Copy code
npm start
Install client dependencies:

bash
Copy code
cd ../client
npm install
Start the React application:

bash
Copy code
npm start
Functionality
Admin Portal
Access the admin portal using the provided admin credentials.
Create and manage student and faculty accounts.
Manage courses, schedules, and other administrative tasks.
Student Portal
Students can log in using credentials created by the admin.
View course information, grades, schedules, etc.
Faculty Portal
Faculty members can access their accounts created by the admin.
Manage courses, assignments, grades, etc.
Contributing
Contributions are welcome! Please follow the guidelines in CONTRIBUTING.md.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Acknowledgements
Thanks to MongoDB for providing a powerful database solution.
Thanks to the open-source community for amazing tools and frameworks
