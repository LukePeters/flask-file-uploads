# Uploading Files with Flask

This repository contains the Flask app starter files for this tutorial on YouTube: [https://youtu.be/GQLRVhXnZkE](https://youtu.be/GQLRVhXnZkE)

## Stylesheet

You can find the CSS file in the `static/` directory or just click here: [https://raw.githubusercontent.com/LukePeters/flask-file-uploads/main/static/styles.css](https://raw.githubusercontent.com/LukePeters/flask-file-uploads/main/static/styles.css)

## Completed Code

You can find code for the completed tutorial in the `completed-tutorial` branch here: [https://github.com/LukePeters/flask-file-uploads/tree/completed-tutorial](https://github.com/LukePeters/flask-file-uploads/tree/completed-tutorial)

## How to Run the App Locally

### Using Pipenv

1. Modify the `Pipfile` to specify your version of Python 3
1. Install Flask: `pipenv install`
1. Activate the virtual environment: `pipenv shell`

### Using virtualenv and pip

1. Create the virtual environment: `virtualenv -p python3 env`
1. Activate the virtual environment: `source env/bin/activate`
1. Install Flask: `pip install Flask`

### Start Flask

Enter these two commands in your terminal:

`export FLASK_APP=app`

`flask run`