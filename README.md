## Introduction

This is a demo repository to teach how to set up social authentication (and request extra user data) in Django using the social-auth-app-django library with minimal configuration. 

## Requirements
* Python3
* [Pipenv](https://pypi.org/project/pipenv/)

## Running the application
1. Clone the project to your machine ```[git clone https://github.com/Jordanirabor/django_social_app]```
2. Navigate into the diretory ```[cd django_social_app]```
3. Source the virtual environment ```[pipenv shell]```
4. Install the dependencies ```[pipenv install]```
5. Update the `settings.py` file with your keys from [Facebook](https://developers.facebook.com/apps), [LinkedIn](https://www.linkedin.com/developers/) and [Instagram](https://www.instagram.com/developer/).
6. Navigate into the `social_app` directory ```[cd social_app]```
7. Start the backend server ```[python manage.py runserver]```
8. Visit the application on the browser - [http:localhost:8000](http:localhost:8000)

## Built With

* [Python](https://www.python.org/) - A programming language that lets you work quickly and integrate systems more effectively.
* [Django](http://djangoproject.org/) - A high-level Python Web framework that encourages rapid development and clean, pragmatic design.