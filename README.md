## Install

- clone the repository
- run in the path where project is : `npm install`
- next, install all the necessary dependencies in path of the project
---
## Dependencies

Express
typescript -D
ts-node -D 
@types/express -D
@types/node -D
nodemon -D


## Setup Reference - (PORTUGUESE ARTICLE)
https://dev.to/melquisedecfelipe/configurando-eslint-no-node-com-express-e-typescript-58p9



## What does the API?

- Create a user with authentication
- Log the user and returns they token access
- Gives a full return of the user data (once he's authenticate) 
- Gives a full statement of the user account

- The user alwarady logged in the app, can request a PIX Key (a brazilian so fast and free transaction), send a PIX to other user (once the user has this PIX Key too)
- And all the applications has just six routes
- Simple, secure and awsome!

## How can I test the API?

You can use Insominia or Postman (or anything like that). 
Once you have one of theese installed, you must test the routes with the uri (it is in the folder "routes" of the project).
