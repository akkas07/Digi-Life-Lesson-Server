# Digi Life Lesson Server

Backend server for the Digi Life Lesson application.

This project contains the server-side code and APIs required for the application.

## Features

* User management
* Admin user management
* User update and delete
* Favorite management
* Database connection
* Data retrieval
* Data update
* Data deletion
* API comments and documentation
* Vercel deployment support

## Technologies Used

* Node.js
* Express.js
* MongoDB
* JavaScript
* Vercel

## Project Structure

```text
Digi-Life-Lesson-Server/
│
├── index.js
├── damo.js
├── package.json
├── package-lock.json
├── vercel.json
├── .gitignore
└── .vscode/
```

## Installation

Install the project dependencies:

```bash
npm install
```

## Run the Project

Start the server:

```bash
npm start
```

You can also run the server directly with:

```bash
node index.js
```

## Environment Variables

Create a `.env` file in the project directory and add the required environment variables.

Example:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

Keep your database credentials and other private information inside the `.env` file.

## API

The project includes APIs for:

* User management
* Admin operations
* Favorite management
* Data retrieval
* Data update
* Data deletion

Most of the API routes are handled in `index.js`.

## Deployment

The project is configured for deployment using Vercel.

The `vercel.json` file contains the deployment configuration.

## Author

Akkas Islam

Digi Life Lesson Server
