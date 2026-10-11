# BlogWebApplication

A blog web application built with Node.js, Express, EJS, and MongoDB.

## Tech stack

- **Server:** Express 4
- **Views:** EJS with `express-ejs-layouts`
- **Database:** MongoDB via Mongoose
- **Auth:** `bcrypt` for password hashing, `jsonwebtoken` + `express-session` for sessions

## Getting started

```bash
npm install
```

Create a `.env` file in the project root:

```
MONGODB_URI=<your mongodb connection string>
jwtSECRET=<a random secret>
```

Then start the server:

```bash
npm start        # node app.js
npx nodemon      # with auto-reload during development
```

The app serves on port `3000`.

## Project layout

```
app.js      application entry point
server/     routes, models, and config
views/      EJS templates and layouts
public/     static assets
```
