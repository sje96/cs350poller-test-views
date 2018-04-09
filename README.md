# cs350poller-test-views

LAB 9

A simple django application to be used as starter code for working on django tutorial part 5 (Automated Testing) and part 6 (Look and Feel).

# Get Started
1. __fork__ this repository to your GitHub account (use the fork button at the top)
2. __clone__ your forked repo to your local working directory
3. cd to repository/project root
4. create a virtual environment for this project
5. Run: `pip install -r requirements.txt`
6. Setup the django app: `python manage.py migrate`
7. Run the test server: `python manage.py runserver`

# Lab 9 Instructions
Work through remaining section in part 5 (testing views) and complete part 6.

1. Begin with the section ==> https://docs.djangoproject.com/en/1.11/intro/tutorial05/#test-a-view
2. Part 6 asks you to modify a file at __polls/templates/polls/index.html__ by adding a style sheet reference, `<link rel="stylesheet" type="text/css" href="{% static 'polls/style.css' %}" />`. Please add this reference instead to __templates/base.html__, in the HEAD section of the html file.

## Django app should be running at http://127.0.0.1:8000


