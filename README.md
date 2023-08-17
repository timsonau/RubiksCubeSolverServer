# RubiksCubeSolverServer

## Description
The Rubik's Cube Solver Server is a microservice that utilizes Flask to provide solutions to any valid configuration of a Rubik's cube.

## installation & usage
- Clone this repository to local.
-Navigate to the top-level directory where app.py resides
-  run app.py by ```python app.py``` for windows, ```python3 app.py``` for mac
-  enter localhost:8080/rubik/solve?cube=[cubestring] in the URL of your browser, where cube string is a string representation of your cube.
-  the site microservice should then show the resulting rotations needed to solve the cube

## Requirments
This app requires the following requirements to run properly
[Flask 2.3.2+](https://pypi.org/project/Flask/)
[Flask-Cors 4.0.0+](https://flask-cors.readthedocs.io/en/latest/)
