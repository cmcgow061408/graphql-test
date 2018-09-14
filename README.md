# graphql-test
Simple GraphQL and GraphiQL example

## 1. Install Node and NPM
`https://nodejs.org/en/`

##2. Install the following packages:
### Express with GraphQL and GraphiQL. 
### In the terminal execute:
`npm install --save express express-graphql graphql`

### Axios JS for http processes:
### In the terminal execute: 
`npm install --save axios`

### NoDemon to automatically restart server when code has changed within our project:
### In the terminal execute:
`npm install --save nodemon`

### json-server to simulate serving data through RESTful services:
### In the terminal execute:
`npm install -g json-server`

_To manual add data to json-server manipulate the db.json file_

## 3. Install dependency for the project.
### In the terminal execute:
`npm install`

## 4. Start up json-server:
### Open a terminal and execute:
`npm run json:server`

## 5. Start up Express with GraphQL and GraphiQL
### Open a terminal and execute:
`npm run dev`
#### Output:
```npm run dev
> graphql-test@0.0.0 dev graphql-test
> nodemon server.js
 
 [nodemon] 1.18.4
 [nodemon] to restart at any time, enter 'rs'
 [nodemon] watching: *.*
 [nodemon] starting 'node server.js'
 Listening...
```

## 6.  You can reach GraphiQL at:
`http://localhost:4000/graphql`

## 7.  You can reach json-server at:
### Home
`http://localhost:3000`
### Resources
  `http://localhost:3000/users`<BR>
  `http://localhost:3000/companies`

