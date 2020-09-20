## Description

A nodejs backend with user authentification using JSON Web Tokens.

## Build with

1. Nodejs
2. Express
3. JSON Web Tokens
4. Mongo DB

## Installation


This application runs on node version `13.12.0` and npm version `6.14.4`

-  clone the app on your computer
-  `cd` into the directory and run `npm install`
-  run `npm start` , the app should run on port 3000


### User management

- Get a list of users -> `[Get]/api/users ` (no auth required)
- Signin -> `[Get]/auth/signin` : takes username and password -> returns signed user Authorization token (string)
- Create user -> `[Post]/api/users` : require email and password
- Get a single user -> `[Get]/api/users/:userId` : requires user's ID as parameter (auth required)
- Update single user -> `[Put]/api/users/:userId` :requires user's ID as parameter (auth and authorization required)
- Delete user ->`[Delete]/api/users/:userId` : requires user's ID as parameter (auth and authorization required)




### Todo

- [ ] Various frontend implementations

