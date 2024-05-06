# Personal Authentication and security app
is a web application that allows user to store secrets locally. It uses Express.js for the backend, EJS for templating, PostgreSQL for the database, and Passport.js for authentication. Users can register, log in, submit secrets, and view his own secrets 

## Features
- User registration and login
- secret submission
- Viewing of submitted secrets
## Technologies Used:

- Express.js
- EJS
- PostgreSQL
- Passport.js

## Installation:
- Clone the repository
- Install dependencies: 'npm i'

### Set up environment variables:
Create a .env file in the root directory
Add the following variables:

- PG_USER=your_postgres_username
- PG_HOST=your_postgres_host
- PG_DATABASE=your_postgres_database
- PG_PASSWORD=your_postgres_password
- PG_PORT=your_postgres_port
- SESSION_SECRET=your_session_secret
- GOOGLE_CLIENT_ID=your_google_client_id
- GOOGLE_CLIENT_SECRET=your_google_client_secret

Start the server: node index.js
Open your browser and navigate to http://localhost:3000
