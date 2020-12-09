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

## Frontend [2] 08/12/20

- npx create-react-app client
- one single command working backend and frontend
- npm i concurrently
- change script "client": "npm start --prefix client"- "dev":"concurrently\"npm run server\" \"npm run client\"
- both working with npm run dev
- use bootswatch link and get theme
- get logo of spacex
- apollo // get started
- cd client
- npm install apollo-boost react-apollo graphql
- error cores policy things
- npm install cors
- //allow cross-origin
  app.use(cors())
  in server.js
- can see data in array! console
- create LaunchItems
- wrap with Fragment // it just not showing in source code?

# 09/12/20

- npm i classnames moment react-moment
- add launch color
- add mission key component(very simple component)
- format date with Moment
- install react router
  npm install react-router-dom
- create Launch component
- connect link and route so that when we click launch detail it can go to lauch.js component
- finish launch js
