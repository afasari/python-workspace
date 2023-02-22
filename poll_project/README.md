# Django Simple Poll Fulls-stack App

## Source

[tutorial](https://prettyprinted.com/tutorials/creating-a-poll-app-in-django)

## Description

We'll have a simple poll app where users can create polls, vote in polls, and view poll results.

The home page after starting server first time.

![Design](./django%20poll.drawio.png)

## What we will build?

a full-stack web application that is a basic Employee Management Aplication with CRUD features:

- Homepage/List Votes (/)
- Take Vote (/vote/{id})
- Result Poll (/results/{id})
- Create Poll {/create}

## How to Run

- `python3 manage.py runserver`

## Useful command

- `pip install django`: install django at the first time
- `django-admin startproject poll_project`: create new poll_project
- `python3 manage.py startapp poll`: create poll for logic
- `python3 manage.py migrate`: migrate db
- `python3 manage.py makemigrations`: make migration from model
- `pip install django-widget-tweaks`: install django widget tweaks for html tweaks
- `sqlite3 db.sqlite3 'select * from poll_poll'`: get data from sqllite3

## Requirement

- pip
- python3
- django-admin
- sqlite3

### Learning

- Templates
- Views
- URLs
- Models
- Model forms
- POST request processing
- Create, Read

## Aha Moments

- django is watching file changes
- database migration create by edit models and run `python3 manage.py makemigrations`

## What's Next?

- Learn Read and Delete
- Create RESTFull API
