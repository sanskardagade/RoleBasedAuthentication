*OVERVIEW*
This project implements a Role-Based Authentication System using Node.js, Express, MongoDB, and JWT. The system allows users to register, login, and access resources based on their roles (e.g., admin, manager, user).

*FEATURES*
User Registration: Users can register with a username, password, and role.
User Login: Secure login with password hashing using bcrypt and token-based authentication using JWT.
Role-Based Authorization: Middleware to protect routes based on user roles.
Token Verification: Middleware to validate tokens and ensure secure access.

*TECHNOLOGY USED*
Node.js: JavaScript runtime.
Express.js: Backend framework.
MongoDB: NoSQL database.


*SETUP*

1️⃣ Clone the Repository
git clone https://github.com/your-username/RoleBasedAuth.git
(Replace your-username with your GitHub username.)

2️⃣ Navigate to the Project Folder
cd RoleBasedAuth

3️⃣ Initialize the Project
npm init -y

4️⃣ Install Dependencies
npm install express mongoose bcryptjs jsonwebtoken dotenv cors

5️ Install Dev Dependencies
npm install --save-dev nodemon

6️⃣Run the Server
npm run dev
