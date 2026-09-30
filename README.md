# Book Search Engine

A MERN-stack app for searching the Google Books API and saving books to your personal reading list. It started as a RESTful API and was refactored to use GraphQL with Apollo Server.

> The original Heroku deployment is no longer available because Heroku ended its free tier. Follow **Getting Started** to run it locally.

## Features

- Search for books with the Google Books API
- Sign up and log in with JWT authentication
- Save books to your account
- View and remove saved books

## Built With

**Front end:** React · Apollo Client · React Router · React Bootstrap
**Back end:** Node.js · Express.js · Apollo Server (GraphQL) · MongoDB · Mongoose · JSON Web Tokens

## GraphQL API

- **Query:** `me` returns the logged-in user and their saved books
- **Mutations:** `login`, `addUser`, `saveBook`, `removeBook`

## Getting Started

**Prerequisites:** Node.js and MongoDB

```bash
git clone https://github.com/Archils/Book-Search-Engine.git
cd Book-Search-Engine
npm install        # installs server and client packages
npm run develop    # runs the API and React app together
```

- React app: http://localhost:3000
- GraphQL playground: http://localhost:3001/graphql

## Screenshots

![Screenshot](demo/21-mern-demo-01.gif)

![Screenshot](demo/21-mern-demo-02.gif)

![Screenshot](demo/21-mern-demo-03.gif)

## Author

**Archils Oburu**
- GitHub: [@Archils](https://github.com/Archils)
- Email: oburuarchils@gmail.com
