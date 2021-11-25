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


# 2. Change he name of the Website to Small Data (The Logo will be changed later).

Please if you know any graphic designer who might be willing to help us design a logo, please invite him/her to join our group on Whatsapp or our server on Discord.

# 3. Add your API credentials.

To add your API credentials to the program follow the instructions under the Chapter called "Obtaining API Keys" on the django-hackathon-starter page on github.

# 4. Upon user login.

- Add a function that executes once a day starting from the day the user signs up for an account. This function should request data (last 100 post on users feed) and store it in our database (as JSON).

# 4. Push editted code to the development devlopment branch of this repo.


