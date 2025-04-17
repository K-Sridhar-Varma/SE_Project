Getting Started

Prerequisites

Node.js and npm installed
MongoDB Database
Instalaltion

Clone the repository to your local machine.
Navigate to the project directory. use two terminal
Cd Client - For Frontend
Cd api - For Backend
Install server dependenciesfor both frontend and backend.
Create a .env file in the root directory with the following content, and replace placeholders with your own values.
MONGODB_URI=mongodb://localhost/your-database-name
Start the server.
ems/api: nodemon start
if the command is not working use PowerShell -ExecutionPolicy Bypass nodemon this command.
Start the Client:
ems/client: npm run dev
The application should now be running. You can access it at http://localhost:5173
The Server is running on http://localhost:4000

