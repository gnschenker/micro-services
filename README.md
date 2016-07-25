# Introduction
This is a sample application demonstrating various concepts like
* Micro services
* Containers
* Message based, asynchronous communication
* Python, Flask, Celery
* REST-ful API

# Install & RUN
Clone this GitHub repository. Open a terminal and navigate to the project folder. Run this command

`docker-compose up`

Open a browser and navigate to `localhost`.

# API
* [GET] /api/tasks                          # get all tasks
* [GET] /api/tasks/{task_id}                # get details for given task id
* [POST] /api/tasks                         # add a new task

  body: {"title": "title]", "description": "[description]"}
  
* [POST] /api/tasks/{task_id}/complete      # complete the given task
