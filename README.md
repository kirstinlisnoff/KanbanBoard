# Kanban Board with JWT Authentication

This full-stack React Kanban board provides a web app where users can log in, manage their tasks across three columbs, and rely on protexted routes for a secure experience. JSON Web Tokens are utilized in this web app to ensure authentication for users.

## Usage 

1. Visit the login page

2. Enter valid credentials

3. Upon success, you’ll be redirected to the Kanban board

4. Your token is stored in localStorage and used for authenticated API requests

5. Log out to clear the session or wait for token expiration to be redirected automatically

## Installation 

```
npm install
npm run build
npm run seed
npm start

```

## Technologies Used 
Frontend: React, TypeScript, Vite, CSS

Backend: Express, Sequelize, PostgreSQL, JWT, Bcrypt

Deployment: Render (Frontend + Backend), PostgreSQL (Render database)

## Deployment 


## Licence
MIT License