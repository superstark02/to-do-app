# To-Do Application using Flask

### Install flask
pip install Flask
pip install flask-sqlalchemy

### Set environment variables
set FLASK_APP=app.py
set FLASK_ENV=development

### Create Databse
In python shell:
from app import app, db
app.app_context().push()
db.create_all()


### Run Application
flask run
