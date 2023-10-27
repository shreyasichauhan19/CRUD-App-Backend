# Node.js Express, Sequelize & PostgreSQL: CRUD Rest APIs

The following table shows overview of the Rest APIs that will be exported:

- GET     `api/tests`	            get all Tests
- GET     `api/tests/:id`         get Test by id
- POST    `api/tests`             add new Test
- PUT     `api/tests/:id`         update Test by id
- DELETE  `api/tests/:id`         remove Test by id
- DELETE  `api/tests`             remove all Tests
- GET     `api/tests/published`   find all published Tests
- GET     `api/tests?title=[kw]`  find all Tests which title contains 'kw'

### Test the APIs
Run our Node.js application with command: `node server.js`.

Using Postman, we're gonna test all the Apis above.

- Create a new Test using `POST /tests` Api


## Project setup
```
npm install
```

### Run
```
node server.js
```
