Flask Docker App

Live Demo: https://flask-aws-app.onrender.com
A simple Flask web app that shows a greeting message. This project is containerized with Docker so it can run anywhere.

What it does:
Displays a greeting message in a web browser
Can run locally or in a container
Deployed live using Render.com

Tech used:
Python 3.11
Flask
Docker
GitHub
Render.com
Running it locally

Clone the repo:
git clone https://github.com/AlharthAli/flask-aws-app.git
cd flask-aws-app


Set up a virtual environment and install dependencies:
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt


Start the app:
python app.py
Open your browser at http://127.0.0.1:5000
Running with Docker

Build the image:
docker build -t flask-aws-app .


Run the container:
docker run -p 5000:5000 flask-aws-app
Then visit http://127.0.0.1:5000

Deployment:
Hosted on Render.com, accessible at: https://flask-aws-app.onrender.com

Notes:
This project is a simple example of containerizing a Python web app.
Good starting point for experimenting with Docker and cloud deployments.
