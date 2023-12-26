# Chat Messenger in ReactJS

## Project Overview

**React Live Messenger** is a real-time chat web application designed to facilitate seamless communication between users. The platform enables users to log in, add friends, and engage in real-time conversations.

## Project Structure

- **client**: Frontend built with React.js
- **server**: Backend developed using Node.js
- **common**: Shared codebase between the client and server components

## Technology Stack

- **Front-End**: React.js
- **Back-End**: Node.js, Express.js, Socket.io
- **Authentication**: JWT (JSON Web Tokens)
- **Database**: PostgreSQL for persistent data storage and Redis for real-time communication

## Getting Started

To run the project:

1. Clone the repository
2. Navigate to the repository and execute `yarn` to install dependencies
3. Ensure a Redis instance is running on `localhost:6379` or define the `REDIS_URL` environment variable
4. Have a PostgreSQL database running, and either set the `DATABASE_URL` environment variable or provide specific details such as `DATABASE_NAME`, `DATABASE_HOST`, `DATABASE_USER`, `DATABASE_PASSWORD`, `DATABASE_PORT`, and `COOKIE_SECRET`
5. Initialize the database by executing the queries in `packages/server/database.sql`
6. Define all environment variables in a file named `.env`
7. Run the server with `yarn dev:server` and the client with `yarn dev:client`

By following these steps, you will have a fully operational React Live Messenger instance running on your local environment.
