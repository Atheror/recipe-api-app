# recipe-api-app
Recipe API Project

## Run lint tool

    docker compose run --rm app sh -c "flake8"

## Initial setup the project

    docker compose run --rm app sh -c "django-admin startproject app ."

## Starting services

    docker compose up

Now Django launch page can be accessed at http://127.0.0.1:8000/