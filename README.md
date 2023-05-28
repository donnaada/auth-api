# LAB - Class 08

## Project: Access Control

### Author: Donna Ada

### Problem Domain

extend the restrictive capabilities of our routes to our API, implementing a fully functional, authenticated and authorized API Server using the latest coding techniques.

Specifically, we want to make the following restrictions:

- Regular users can READ.
- Writers can READ and CREATE.
- Editors can READ, CREATE, and UPDATE.
- Administrators can READ, CREATE, UPDATE, and DELETE.

### Tasks

1. Fix the Bugs
2. Secure the JWT Tokens

### Links and Resources

- [GitHub Actions ci/cd](https://github.com/donnaada/auth-api/actions)
- [back-end server url](https://api-server-6a4s.onrender.com)
-

### Collaborators

Referenced Ryan Gallaway's Demo Code

### Setup

#### `.env` requirements (where applicable)

Port variable located within .env.sample

#### How to initialize/run your application (where applicable)

- e.g. `npm start`

#### How to use your library (where applicable)

Clone repo, `npm i`, `npm run db:create`, then run `nodemon` in terminal

#### UML

![Lab UML](./assets/uml.png)
