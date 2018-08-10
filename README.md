README FOR CAPSTONE PROJECT API

Premise: a multiplayer shooting game

User Stories:
-As a user, I want to log in to the shooter game
-As a user, I want to be able to play against other players in real time
-As a user, I want to be able to have a username separate from my email
-As a user, I want to keep track of career wins or takedowns

Links:
Client Repo
https://github.com/matthewjramos/capstone-client
Client URL
https://matthewjramos.github.io/capstone-client
API Repo
https://github.com/matthewjramos/capstone-api
API URL
https://wdi-capstone-api.herokuapp.com/

Technologies used:
Express
Javascript

Problems encountered: 
-Initially, was using the Phaser 3 game engine with Socket.io, but ran into compatibility issues
  -This led to a removal of multiplayer options

Routes:

  GET     /games
  POST    /games
  PATCH   /games/:id
  DELETE  /games/:id
      
  

