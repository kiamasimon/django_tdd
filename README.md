## Test Driven Development Illustration In Django(Selenium/ChromeDriver)
    `Includes some units tests and functional test samples'
### Getting Started

The following instruction will help you set up the project as a developer.
#### Prerequisites

` Before you clone this project you need to: `

`Install Python 3.7` 

`Create a virtual environment`

`Make sure your virtualenvironment is activated everytime you work on this project`

#### Managing Dependencies

After cloning the project, on your terminal navigate to project base folder (where requirements.txt is) To install dependencies run the following command:

`pip install -r requirements.txt`

In case you add dependencies to the project, make sure you update requirements.txt by running the following command.

`pip freeze > requirements.txt`

Make sure you use git flow, the latest code will be on develop branch.

#### Configuration File

Django uses settings.py files for configuration. Do not edit this file, instead create a file named local_settings.py in the folder where settings.py is located and copy everything that is located inside settings.py apart from the last lines which start with try.

Every time you want to change configuration use local_settings.py

#### Version Control

Since we are using git - make sure you setup git flow on your local machine. We will be using feature development structure. 


#### Running Migrations

Before you can run the project in development environment, you need to set up the migration. To create initial migration run the following command:

`python manage.py makemigrations`

To sync you migration with the database use the following command:

`python manage.py migrate`

#### Built With

    Python 3.7 - Programming Language
    Django Web Framework - The web framework used
    Git Flow Cheatsheet - Version Control
    
#### Removing All Migrations Files

Sometimes in the course of development you find yourself at point where you need to clear migrations. You can use the following commands:

`find . -path "*/migrations/*.py" -not -name "__init__.py" -delete`

`find . -path "*/migrations/*.pyc"  -delete`

#### Authors
* Simon K Irungu
    

