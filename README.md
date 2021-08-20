# todoApplication
A simple To do Application using python and Flask

### Setting up the Environment
1. Install latest version of Python.
2. Download sqlite3 and add it to the path.
3. Open the project folder and run this command in command prompt to create a virtual environment.
```console
todoApplication> python -m virtualenv venv
```
4. Now activate the virtual environment.
```console
todoApplication> venv\Scripts\activate
```
5. Now install `flask` and `flask-sqlalchemy` using pip command.
```console
(venv) todoApplication> pip install flask flask-sqlalchemy
```
6. Run the following command to start the application.
```console
(venv) todoApplication> python app.py
* Serving Flask app 'app' (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: on
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 588-443-625
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```
7. Open `localhost:5000/` or `http://127.0.0.1:5000/` in your browser to view the application
