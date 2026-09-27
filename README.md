Digi Life Lesson Server

Backend server for the Digi Life Lesson application.

This project provides the API and server-side functionality required for managing users, lessons, favorites, authentication, and other application features.

Features
User management
Admin user management
User update and delete functionality
Favorite lesson API
Database connection
API endpoints for application data
Basic API documentation and comments
Vercel deployment support
Technologies Used
Node.js
Express.js
MongoDB
JavaScript
Vercel
Project Structure
Digi-Life-Lesson-Server/
│
├── index.js
├── damo.js
├── package.json
├── package-lock.json
├── vercel.json
├── .gitignore
└── .vscode/
Installation

Clone the repository:

git clone https://github.com/akkas07/Digi-Life-Lesson-Server.git

Go to the project directory:

cd Digi-Life-Lesson-Server

Install the required packages:

npm install
Run the Project

Start the server with:

npm start

For development, you can also use:

node index.js
Environment Variables

Create a .env file in the project root and add the required environment variables.

Example:

PORT=5000
MONGODB_URI=your_mongodb_connection_string

Do not upload your .env file or expose database credentials and other private keys in the repository.

API

The server contains APIs for different application features, including:

User management
Admin operations
Favorite management
Data retrieval
Data update
Data deletion

API routes are available in index.js.

Deployment

The project can be deployed using Vercel.

The vercel.json file is included for deployment configuration.

Author

Akkas Islam

GitHub: https://github.com/akkas07
