#Assessment: Flask Microblog 
This assessment introduces Flask through the [Flask Mega Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world) series, a course designed by Miguel Grinberg. Each chapter of this series will serve as both a reading, and assignment. Your instructors will guide you through any difficulties throughout the course.

### Part 1: Hello World
The goal of this chapter is to:
<ul>
<li>Learn how to set up a Flask project.</li>
<li>Run a simple Flask web application.</li>
</ul>
### Part 2: Templates
<ul>
<li>Generate a more elaborate web page that has a complex structure and many dynamic components.</li>
</ul>
### Part 3: Web Forms
<ul>
<li>Uses forms to allow users to login and submit blog posts.</li>
<li>Introduces FlaskWTF</li>
</ul>

### Part 4: Database

### Part 5: User Logins



##Getting Started

## Installing

Clone your `microblog` repo to your own local machine, and create a python 3 virtual environment at the top level of your microblog folder, by using pipenv rather than using `python3 -m venv` or virtualenv. 
    
    piero@Piero-MBP: Projects $ mkdir microblog
    piero@Piero-MBP: Projects $ cd microblog
    piero@Piero-MBP: microblog $ pipenv install --python 3.7

    Creating a virtualenv for this project…

    Pipfile: /Users/piero/Projects/microblog/Pipfile
    Using /usr/local/Cellar/python/3.7.3/Frameworks/Python.framework/Versions/3.7/bin/python3.7m (3.7.3) to create virtualenv…
    ⠦Running virtualenv with interpreter /usr/local/Cellar/python/3.7.3/Frameworks/Python.framework/Versions/3.7/bin/python3.7m
    Using base prefix '/usr/local/Cellar/python/3.7.3/Frameworks/Python.framework/Versions/3.7'
    New python executable in /Users/piero/Projects/microblog/.venv/bin/python3.7
    Also creating executable in /Users/piero/Projects/microblog/.venv/bin/python
    Installing setuptools, pip, wheel...
    done.
    Virtualenv location: /Users/piero/Projects/microblog/.venv
    Creating a Pipfile for this project…
    Pipfile.lock not found, creating…
    Locking [dev-packages] dependencies…
    Locking [packages] dependencies…
    Updated Pipfile.lock (a65489)!
    Installing dependencies from Pipfile.lock (a65489)…
    🐍   ▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉ 0/0 — 00:00:00
    To activate this project's virtualenv, run pipenv shell.
    Alternatively, run a command inside the virtualenv with pipenv run.
    Install the Flask library into your virtual environment: 
    piero@Piero-MBP: microblog $ pipenv install flask
    Installing flask…
    Collecting flask
        Using cached https://files.pythonhosted.org/packages/9a/74/670ae9737d14114753b8c8fdf2e8bd212a05d3b361ab15b44937dfd40985/Flask-1.0.3-py2.py3-none-any.whl
    Collecting click>=5.1 (from flask)
        Using cached https://files.pythonhosted.org/packages/fa/37/45185cb5abbc30d7257104c434fe0b07e5a195a6847506c074527aa599ec/Click-7.0-py2.py3-none-any.whl
    Collecting itsdangerous>=0.24 (from flask)
        Using cached https://files.pythonhosted.org/packages/76/ae/44b03b253d6fade317f32c24d100b3b35c2239807046a4c953c7b89fa49e/itsdangerous-1.1.0-py2.py3-none-any.whl
    Collecting Werkzeug>=0.14 (from flask)
        Using cached https://files.pythonhosted.org/packages/9f/57/92a497e38161ce40606c27a86759c6b92dd34fcdb33f64171ec559257c02/Werkzeug-0.15.4-py2.py3-none-any.whl
    Collecting Jinja2>=2.10 (from flask)
        Using cached https://files.pythonhosted.org/packages/1d/e7/fd8b501e7a6dfe492a433deb7b9d833d39ca74916fa8bc63dd1a4947a671/Jinja2-2.10.1-py2.py3-none-any.whl
    Collecting MarkupSafe>=0.23 (from Jinja2>=2.10->flask)
        Using cached https://files.pythonhosted.org/packages/ce/c6/f000f1af136ef74e4a95e33785921c73595c5390403f102e9b231b065b7a/MarkupSafe-1.1.1-cp37-cp37m-macosx_10_6_intel.whl
    Installing collected packages: click, itsdangerous, Werkzeug, MarkupSafe, Jinja2, flask
    Successfully installed Jinja2-2.10.1 MarkupSafe-1.1.1 Werkzeug-0.15.4 click-7.0 flask-1.0.3 itsdangerous-1.1.0

Also, install the flake8 linter with `pipenv install flake8`
   
    piero@Piero-MBP: microblog $ pipenv install flake8




##Deployment
To run the application in terminal:

    FLASK_APP=microblog.py 
    
Next, execute:
        
        flask run

Open the site by entering the following URL in your web browser's address bar:

        http://localhost:5000/ 

## Built With:
<ul>
<li>Python</li>
<li>

[Flask](https://palletsprojects.com/p/flask/) -- a lightweight WSGI web application framework. It is designed to make getting started quick and easy.
</li>
<li>

[FlaskWTF](https://flask-wtf.readthedocs.io/en/stable/)--Integrates Flask and WTForms.
</li>
</ul>

## Authors
<ul>
<li>Eileen Tallman</li>
<li>Piero Madar--Assessment Material, Kenzie Academy</li>
</ul>

##Acknowledgement
<li>Miguel Grinberg -- Flask Mega Tutorial Author</li>
