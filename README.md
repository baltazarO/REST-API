# Drinks REST API

Author: Baltazar Ortiz

This will be a very basic REST API that uses a database. Underlying technologies: Python3,
Flask, SQLite, HTTP. I am going to assume you will be using pipenv. But you could probably find a way to use a Docker container to host this app.

## Step 1: Installs

1. Install Flask and pipenv
2. Open terminal
3. Enter pipenv shell \
`pipenv shell`

4. Run the following commands: \
`pipenv install request` \
`pipenv install flask_sqlalchemy` \
`pipenv install flask` 

## Step 2: Startup script

Run startup.py to create database instance or in this case file: \
`python3 startup.py`

## Step 3: Run the script

Run the command below and go to your web browser (or you can use Postman or curl). Enter
localhost:5000 in the browser url section. This will make a HTTP request, specifically a GET request, to the flask app. To stop the app, go to the terminal and press CTRL-C. \

A word on environment variables... Flask needs to know which script to run which is why we will use environment variables. Notice we are using a development environment. Do 
not use this environment for end-users. If you want to deploy this code, use a production environment.

`bash rundev.sh`
