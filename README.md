# MyProject

A generated Bluemix application

[![](https://img.shields.io/badge/bluemix-powered-blue.svg)](https://bluemix.net)

## Run locally as Flask application
```bash
pip install -r requirements.txt
export FLASK_APP=server
gunicorn -b 0.0.0.0:8080 server:app
```