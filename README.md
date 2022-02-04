# Full Stack Engineer Challange

> This repository contains the instructions for the buuk engineer challange.

**Note:** Please don't fork this repository, or create a pull request against it. Once the coding challenge is completed, you can provide a Repository Link via email.

## DevOps Exercise
The backend, database and frontend applications should be running in docker containers.

The `docker-compose.yml` file should define both the backend and frontend as services, which will be automatically built and started upon calling docker-compose up. A container for a DB should be defined here as well.

**Things you don’t have to worry about:**
- CI configuration / Deployment
- Secret Management

## Backend Exercise
Implement an API using `Node/Express` with `Typescript` which handles the follwing tasks:
1. It accepts and handles JSON payload containing book information
2. It accepts and handles user credentials for logging in
3. It has an endpoint for retreiving all books (secured)

- The received book should be stored in a database of your choice.
- Write at least 1 test

#### Example Payload
```json
{
  "isbn": "123456789",
  "title": "I love coding",
  "author": "John Doe",
  "price": "14.99€"
}
```

**Things you don't have to worry about**
- CI configuration / Deployment
- Authentication for the book REST endpoint

## Frontend Exercise
Implement a basic Single Page Application (SPA) using `React` (either plain React or NextJs) wich does the follwing things:
1. It provides a login screen and handles authentication
2. It displays all stored books on a dashboard (if authenticated)

- Please use React hooks
- Write at least 1 test

**Things you don’t have to worry about:**
- Making it super pretty: The UI should be clean and properly aligned however it does not need any extraneous CSS and/or animations. You can use any UI framework you like.
- CI configuration / Deployment
