# RESTful API to keep track of To-Do list using Node.js and MongoDB

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Building a RESTful API to create, update, delete tasks with inputs name and status.

	POST /tasks - Creates a task with inputs name and status (status is set to 'pending' by default)
	GET /tasks - Get all the tasks
	GET /tasks/taskId - Read a specific task
	PUT /tasks/taskId - Update a specific task
	DELETE /tasks/taskId - Deletes a specific task

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# How to run

Open Command prompt 1
Start MongoDB by running - mongod
Open Command prompt 2
Start Node.js by running - npm run start

Open Postman (Chrome extension) and call
http://localhost:3000/tasks (POST) to create a task with inputs name and status
http://localhost:3000/tasks (GET) to get all the tasks
http://localhost:3000/tasks/taskId (GET) (taskId - can be found from the already created tasks) to read a specific task
http://localhost:3000/tasks/taskId (PUT) (taskId - can be found from the already created tasks) to update a specific task with different name and status
http://localhost:3000/tasks/taskId (DELETE) (taskId - can be found from the already created tasks) to delete a specific task

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
