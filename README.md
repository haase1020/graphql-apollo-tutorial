# graphQL-apolloclient-template

## Youtube Tutorial

[YOUTUBE VIDEO](https://www.google.com)

## Stack

FrontEnd:

- React
- Apollo Client
- GraphQL

BackEnd:

- NodeJS
- ExpressJS
- GraphQL
- Apollo Server

### run server

- in server directory, run `node index.js`. This will run on localhost:6969.
- to run GraphiQL then go to `http://localhost:6969/graphql`.

### example query to get all users:

`query { getAllUsers { firstName lastName email } } `

### add a user:

`mutation { createUser(firstName: "Mandi", lastName:"Haase", email:"mandi@gmail.com",password: "password"){ firstName lastName email } }`
