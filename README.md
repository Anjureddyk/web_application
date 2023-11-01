# web_application

## Python Web Application CI/CD with GitHub Actions
This repository contains a basic Python web application that displays 'Hello, World!' and a CI/CD pipeline set up using GitHub Actions. The application is built with Flask, and automated tests are performed using pytest.

## Application
The web application is defined in `app.py`. It is a simple Flask application that serves a "Hello, World!" message when accessed in a web browser.

## Automated Testing
Automated testing is an integral part of this CI/CD pipeline. We have created a test file test_app.py to verify that the application displays 'Hello, World!' correctly.

## GitHub Actions Workflow
We have set up a GitHub Actions workflow to automatically build and test the application on every push to the main branch. The workflow file, named .github/workflows/python-app.yml, defines the CI/CD pipeline.

## The workflow performs the following steps:

* Sets up the Python environment (Python 3.10).
* Installs required dependencies, including flake8 for linting and pytest for testing.
* Lints the code using flake8 to ensure coding standards.
* Executes tests using pytest to verify the functionality of the web application.

## Running the Workflow
Whenever you push changes to the main branch, the GitHub Actions workflow will be automatically triggered. It will build and test your Python web application. You can monitor the workflow's progress in the "Actions" tab of your GitHub repository.

