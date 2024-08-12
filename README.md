# Todo Task Management web application
> This web application created using MERN STACK  with typescript

### LANGUAGES, FRAMENWORK AND LIBRARY USED IN PROJECT
>React.js

>Node.js

>Express.js

>MongoDB

>Typescript




**React + TypeScript**

**Node + Express + TypeScript**



## To get started follow this steps

### step1: clone repository
```
git clone "https://github.com/rohitp-18/task.git"
```

### step 2: run commands
```
npm i
cd front && npm i
```
### Step 3: to start backend or server side
```
npm start
```
> for development with nodemon
```
npm run back
```

### Step 4: Create .env file in back/config folder
> Environment variables

**MONGO_URL** - for mongoose connection string connect eg. "mongodb://localhost:27017/database-name"

**PORT** - for run application on browser prefered 5000


## EndPoints 
| Method | endpoint | uses |
| ------ | ---------| ------ |
| GET    | _/tasks/_ | get all tasks from mongodb |
| POST   | _/tasks/_ |  create task |
| GET   | _/tasks/:id_ | get single task |
| PUT   | _/tasks/:id_ | update task |
| DELETE   | _/tasks/:id_ | delete task |
