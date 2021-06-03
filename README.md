## simple-web-app-flask
Simple Web Application
This is used in the demonstration of simple web app.

steps....

Install all required dependencies
Install and Configure Web Server
Start Web Server
1. Install all required dependencies
Python and its dependencies

apt-get install -y python python-setuptools python-dev build-essential python-pip python-mysqldb
2. Install and Configure Web Server
Install Python Flask dependency

pip install flask
pip install flask-mysql
Copy app.py or download it from source repository
Configure database credentials and parameters
3. Start Web Server
Start web server

FLASK_APP=app.py flask run --host=0.0.0.0
4. Test
Open a browser and go to URL
