- npm i graphql express-graphql express axios
- npm i -D nodemon
- stript change
  "start": "node server.js"
  "server":"nodemon server.js"
- server.js
- http://localhost:5000/graphql (graphiql :true so it's going to come up with grapiql application)
- {
  launches{
  flight_number,
  mission_name
  }
  }
  can play in graphiql

- {
  launch(flight_number:2){
  mission_name
  }
  }
