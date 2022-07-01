# Workshop #14
Your goal is to implement rating component:
- Showing current rating (from movie.rating)
- Ability to rate movie (1-5) and change it in DB and in the client
  - Create endpoint that update rating in the movie using title and new rating
  - Add 5 empty stars (you have empty star asset in [Folder](client/src/assets))
  - User clicks on 1 to 5 star, and it will trigger request from webapp to server to update
  - Update rating according to what was chosen

#### Before starting workshop you need
1. Run `npm install` in root folder
2. Run `cd client && npm install`
3. go to config.json and change user/password/database name if it's different from ours.
4. run migration with  `npx sequelize-cli db:migrate`
5. run seed: `npx sequelize-cli db:seed:all`


### To start project:
- run docker with mysql
- to start client development run `cd client && npm start`
- to start server run in root folder `npm run` or `npm run:dev` 
