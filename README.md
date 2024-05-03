# angular-14-example - verification-boilerplate

Angular 14 Auth Boilerplate - Sign Up with Verification, Login and Forgot Password

Working towards a .NET 8 Web API

# Last updated

- 03-05-2024

# Functionality of the Web App

- The Web API was made without the ASP.NET Core Identity using custom JWT middleware
- JWT authentication with refresh tokens
- Refresh token rotation
- Revoked token reuse detection
- Email sign up and verification
- Forgot password and reset password functionality
- Role based authorization with two roles "User" and "Admin"
- CRUD Account management routes with role based access control

# Tech used for this Web Client

- Node.js version 18.19.1
- Volta for Node Version management
- Angular 14 is the JS framework for this frontend
- TypeScript
- Jasmin for Unit Testing
- Karma for configuration and HTML Test report coverage
- Traditional Webhotel for Hosting
- VS Code is my developement tool

# Tech used for Web API, DB, Hosting and DevOps

- .NET 8
- SQLiteL for the DB
- Traditional Webhotel for Hosting
- VS Code as developement tool
- Swagger API documentation with routes

# Installing

- Make sure you have a new version of Node installed
- Download the code by zip or fork
- Run the command npm install by the command promt

# Development server:

- npm run start

- You can view the development server at `localhost:4200`

# Production build:

- npm run build

The production build will be in the folder: dist

# Testing

- npm run test

Testing with Karma and Jasmine

Test example 1 - src/test.example.spec

Test example 2 - src/app/test.example.spec

Note: Testing was not working with Angular 15 !

Maybe could be solved adding a test.spec.ts




