# API DOCUMENTATION

## Endpoints

### USER REGISTARTION
1. Endpoint : https://claw-backend-a336.onrender.com/register
2. method: POST
3. description: Register a new user
4. Request Body: {
  "id":uuidv4(),
  "username":"enter username",
  "password":"enter password",
  "role":"enter role"

 }
 5.Response: "User created successfully"

 ### USER LOGIN
 1. Endpoint: https://claw-backend-a336.onrender.com/login
 2. method:"POST"
 3. description: Log in a user and generates a JWT token
 4. Request.body: {
      "username":"exist username",
    "password": "user password"
    }
5. Response: "token"

### CREATE TODO
1. Endpoint: https://claw-backend-a336.onrender.com/todos
2. method: "POST"
3. description: Creates a new todo item
4. Request Body: {
    "id":uuidv4(),
   "task":"enter task name",
   "isCompleted":"status"
   }
5. Response: if Authorized Todo created successfully

### GET ALL TODOS
 1.Endpoint: https://claw-backend-a336.onrender.com/todos
   2. method: "GET"
   3. description: Retrive all todo tasks for authorized users
   4. Response: List of tasks

### UPDATE TODO
1. Endpoint: https://claw-backend-a336.onrender.com/todos/:id
2. method: "PUT"
3. description: updateds an existing task
4. request Body: {
    "task":"task name",
   "isCompleted":"status"
   }
5. Response : if authorized updated successfully
### DELETE TODO
1.Endpoint: https://claw-backend-a336.onrender.com/todos/:id 
2.method: "DELETE"
3.description: delete task by id
4. Response: if Authorized task deleted successfully


** DEPLOYMENT DOCUMENTATION **


1.initially clone the project https://github.com/vkonga/claw-assignment-fullstack
# BACKEND DEPLOYMENT:
## STEPS:
2.Later change directory to claw-assignment/claw-backend.
3. Install dependencies sqlite3, sqlite, express, cors, jwtwebtoken, uuid, bcrypt,etc..
4. Enter a coomand nodemon index.js to run.
5. Create a git repository in GITHUB an push code to github.
6. Deploy project using RENDER

# FRONTEND DEPLOYMENT: url:https://claw-frontend-bh33.vercel.app/signin
1. change directory to claw-assignment
2. create react project npx create-react-app project-name
3. install necessary dependencies...
4. Create a git repository in GITHUB an push code to github.
5. Deploy project using VERCEL
6. Create a git repository in GITHUB an push code to github.
