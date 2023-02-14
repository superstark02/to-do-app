# To-Do Application using Flask

### Create an environment
- py -3 -m venv venv
- venv\Scripts\activate
- 
### Install flask
- pip install Flask
- pip install flask-sqlalchemy

### Set environment variables
- set FLASK_APP=app.py
- set FLASK_ENV=development

### Create Databse
In python shell:
- from app import app, db
- app.app_context().push()
- db.create_all()


### Run Application
flask run
