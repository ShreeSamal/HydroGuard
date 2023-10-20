[![Website](https://img.shields.io/badge/View-Website-blue)](https://sample-project.s3-web.us-east.cloud-object-storage.appdomain.cloud)

# Getting Started with My Flask App

My Flask App is a simple Flask web application that can be used as a template or starting point for working with the Flask web framework. Follow the instructions below to set up and run the app in a virtual environment.

## Run My Flask App for Local Development

### Pre-requisites

1. [Install Python](https://www.python.org/downloads/)

### Set up a Virtual Environment

To keep your project dependencies isolated, it's a good practice to create a virtual environment. If you haven't already, you can create a virtual environment named 'env' using the following commands:

```bash
# On macOS and Linux
python3 -m venv env

# On Windows
pip install virtualenv
virtualenv env
```


#### Run the App

Execute following commands
```
env\Scripts\activate 
set FLASK_APP=app.py
set FLASK_ENV=development
flask run
```
Open a web browser and enter `http://localhost:5000`.

#### Install Dependencies

``` 
pip install -r requirements.txt
```


### Live Demo

URL: https://hydroguard.onrender.com

Credentials to run on local machine -
 - For Society
   - email- "kaushal@mail.com"
   - password- "kaushal"
 - For Government
   - email- "shree@mail.com"
   - password- "shree"
  
### Current Features

- **Complaint System for User:** A streamlined user-friendly complaint system with prompt resolution and feedback.

- **Admin Dashboard for Society Head:** A comprehensive admin dashboard that enables real-time monitoring of society water quality for effective management.

- **Admin Dashboard for Government Body:** A comprehensive admin dashboard that enables real-time monitoring of overall locality's water quality for effective management.

- **Water Quality Analysis Using Different Sensors:** The system employs various sensors for water quality analysis, including:
  1. pH Sensor
  2. Turbidity Sensor
  3. TDS Sensor (Total Dissolved Solids)
  4. Temperature Sensor
  5. Water Flow Sensor


### Run the Sample React App on IBM Cloud for Free

#### Pre-requisites

1. IBM Cloud Account:
   - [Create free IBM Cloud account with $200 USD in credits](https://developer.ibm.com/callforcode/get-started/)
2. [Install Node and NPM](https://nodejs.org/en/download/)

#### Build the App for production

- Start a terminal/CMD in `~/Project-Sample/sample-react-app` directory.
- Execute command `npm install` and `npm run build`.

A production ready app's build folder with all dependencies will be created in the `~/Project-Sample/sample-react-app/build` directory.

#### Deploy the App on IBM Cloud

The App can deployed on IBM Cloud for free with following;

1. [IBM Cloud Object Storage](./docs/IBM_CLOUD_OBJECT_STORAGE_DEPLOYMENT.md)
