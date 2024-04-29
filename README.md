# Exercise Engine
## Contents

- [Summary](#summary)
- [Running Locally](#running-locally)

## Summary

This is a project for **"CS/INFO 4300 class at Cornell University"**, where we worked
in a 5 person software development team to build an information retrieval system of our
choosing. We decided to return the most similar exercises given an exercise queried either
chosen from the dropdown or given freeform. Our website uses HTML, JS, and CSS to make
backend requests and display the results in a aesthetically pleasing way. We allow for
filtering based on muscle group, difficulty, and equipment used and display the reviews
taken from [bodybuilding.com](https://bodybuilding.com), the exercise description, the muscle groups and equimpent used, the most relevant youtube search, and the similarity score. The backend is a python app built using the Flask framework which takes in our Selenium-webscraped dataset and performs SVD text-mining on it. It then uses the embeddings to return the top 5 most similar results that fit within the filters. This project taught us lots about utilizing agile development within a large software development team to build a product. We discovered how to webscrape data, build an appealing frontend, and utilize the methods learned in class to produce an IR system on the backend.

## Images

### Home Page
![Home Page Image](/backend/static/images/Home%20Page.png)

### Results Page
![Results Page Image](/backend/static/images/Results%20Page.png)

## Running locally

### Step 1: Download the source code
Clone or download a zip file of the source code onto your device


### Step 2: Set up a virtual environment
Create a virtual environment in Python (or using conda if more familiar):

Run `python -m venv <virtual_env_name>` in your project directory to create a new virtual environment, remember to change <virtual_env_name> to your preferred environment name.

### Step 3: Install dependencies
You need to install dependencies by running `python -m pip install -r requirements.txt` in the backend folder.

## Command to run project locally (in backend folder): 
```flask run --host=0.0.0.0 --port=5000```

## Online Hosting
The website server is hosted on the [Class Website](http://4300showcase.infosci.cornell.edu:5212/).


## Authors
### Matthew McAuley
mwm223@cornell.edu

### Sharanya Dabas
sd699@cornell.edu

### Eman Abdu
ema88@cornell.edu

### Alex Kushnirsky
ask256@cornell.edu

### RJ Powers
rgp58@cornell.edu
