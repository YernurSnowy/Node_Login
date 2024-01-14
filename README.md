# Registration and Login System
**Group:** SE-2211 <br />
**Creators:** Yernur Koishybayev, Alinur Alipov, Alikhan Dosmaganbetov

## System Description
It is a Node JS application which is connected to Postgres (SQL) database. The database is used to store user details including their names, email addresses and passwords in order for them to log on to the application.

## Node libraries
+ bcrypt - To hash user password to make them secure
+ express-session - To store session details in a session cookie object
+ express-flash - To display flash messages to the user
+ passport - To authenticate users
+ passport-local - To implement a local authentication strategy for our application

## Usage 
```
npm init
npm i express
npm install -D nodemon
npm i ejs
npm i dotenv pg
npm i bcrypt
npm i express-session express-flash
npm i passport passport-local
```

## Installation and Launch
1. Download files from the repository
2. Download [PostgreSQL](https://www.postgresql.org/) and [Node.js](https://nodejs.org/en)
3. In the terminal, write the lines indicated above in the **Usage** block
4. In `.env` file change the already entered data to your PostgreSQL data
5. In the `package.json` file, replace the script written on line 7 with the following lines:
   ```
    start": "node server.js",
    "dev": "nodemon server.js"
   ```
6. Write `npm run dev` into the terminal
7. Go to localhost: 4000 in the browser
