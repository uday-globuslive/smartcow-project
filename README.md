# DevOps-Assignment

This DevOps Assignment represents exactly the type of tasks which you might have to do as a DevOps Engineer at SmartCow. In this repo, you will find a simple Python - Flask Web App, which reads the current RAM and CPU usage and a React frontend which shows the statistics in the browser.

## How to run?

### Python Backend 
1. `pip install -r requirements.txt`
2. `python app.py`
3. Visit `http://localhost:8000/stats`

### React Frontend
1. `npm install`
2. `npm start`

## Task 1 - Dockerize the Application

The first task is to dockerise this application - as part of this task you will have to get the application to work with Docker and Docker Compose. 

Hint/Optional - Create 2 separate containers. One for the backend and other for the frontend. It's okay to serve the React app using `npm start` at this point.

It is expected that you create another small document/walkthrough or readme which helps us understand your thinking process behind all of the decisions you made. 

The only strict requirement is that the application should spin up with `docker-compose up --build` command. 

You will be evaluated based on the
* best practices
* ease of use
* quality of the documentation provided with the code


## Task - 2 
The next task is to get this app to work with UWSGI or Gunicorn and serve the react frontend through Nginx. 

This time the React container should also perform `npm build` every time it is built.

Hint/Optional - Create 3 separate containers. 1 for the backend, 2nd for the proxy and 3rd for the react frontend.

You will be evaluated based on the

* best practices
* ease of use
* quality of the documentation provided with the code