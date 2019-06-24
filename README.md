# backend-thermometer

This tiny Flask web application fetches the most recent (as of 15 mins ago) temperature data from an AWS DynamoDB table and returns the data as JSON.

## Installation

This project uses virtualenv (python3) to manage packages. Install packages with
```shell
python3 -m venv <myenv>
source <myenv>/bin/activate
pip install -r requirements.txt
```

## How to run

You can start the web server with the following command
```shell
FLASK_APP=thermo_app.py flask run
```
