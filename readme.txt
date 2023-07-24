pip install virtualenv 
virtualenv env
.\env\Scripts\activate
pip install flask-sqlalchemy  # to use database in flask, need to install this

to create data base go to python shell(https://flask-sqlalchemy.palletsprojects.com/en/2.x/quickstart/)
python
from app import db
db.create()



pip install gunicorn
pip freeze >requirements.txt    # it will craete a requirements.txt file and automatically fill the all requirements based on app, It helps to deploye the website.
