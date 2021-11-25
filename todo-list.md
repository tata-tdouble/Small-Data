You are welcome to our To-Do List.

We are happy you interested in this project. 

Below is a list of the most pressing task in order of priority that must be complete for this project to move forward. 

# 1. Clone and set up the django-hackathon-starter repository on your computer.

<b> Clone the repo.</b>

$ git clone https://github.com/DrkSephy/django-hackathon-starter.git
$ cd django-hackathon-starter

<b> Install the requirements</b>

$ pip install -r requirements.txt

<b> Install bower</b>

$ npm install -g bower
$ bower install

<b> Perform database migrations</b>

$ python manage.py makemigrations
$ python manage.py migrate


# 2. Remove all the Sign-in/Sign-up APIs Except that of Facebook and Add your Facebook API credentials.</b>

To add Facebook API credentials to the program follow the instructions under Chapter called "Obtaining API Keys" on the django-hackathon-starter page on github.


# 3. Upon user login (after user logsin with facebook)

- create a function that request data (last 100 post on users feed)from Facebook once every day and stores the data in our database (as JSON).

# 4. Push editted code to the development devlopment branch of this repo.
