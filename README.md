

PROJECT
========

![Screenshot of portfolio website](/static/images/Screenshot.png?raw=true "Final result")


## 1. Description
This portfolio project is an assignment for Udacity's Front End Web Developer Nanodegree.
It is build using:
- Webapp2
- Jinja2 (currently not really used)
- Bootstrap

I also used Grunt to create several version of the same images but decided to not include it in here.

Its purpose is to illustrate the concept of responsive websites.

The final result has been deployed on Google Cloud and is visible [here](https://jeremies-portfolio.appspot.com/).



## 2. How to install
To obtain the files in this directory, you can either fork the repository in your own directory or download a zip file to your own machine and extract it. Either way, you should have the unzipped folder on your machine to be able to run it.

To run this website as intended, you will need to download and install the following:
- Python 2.7
- Google App Engine SDK
- gcloud command line interface
- Webapp2
- Jinja2

Your folder should contain three files and two folders called "Static" and "Templates".

1. main.py: sets up the Webapp and Jinja frameworks on which the application runs
2. app.yaml: declares the dependencies to the App Engine
3. README.md: a copy of this document

The "Static" folder contains two sub-folders: images, that holds all the pictures used for the site, and bootstrap, that contains a config file and two sub-olders all the scripts and css files used in the application.
The "Templates" folder contains index.html, currently the only html template.

## 3. How to get started 
There are currently three ways of getting started.

### 1. Open index.html in your browser.   
It will provide you with most of the experience. However, clicking on the logo will not bring you back to the page but will give you an error message.  
### 2. Run the app locally.  
- Navigate to the folder conatining main.py 
Run `>>> dev_appserver.py app.yaml.py`  
- The app will run on the [port 8080](http://localhost:8080) and the datastore on [port 8000](http://localhost:8000/datastore)    
### 3. Deploy the app to Google Cloud.   
- Log into your Google Cloud Plateform account and create a project.  
- Take note of the project's ID  
- Run `>>> gcloud app deploy --project your-project-ID`    


## 4. More information
For now, the site only contains a single page. However, I plan on building it further as I move forward in this or other Nanodegrees. 
I plan on adding:
- A Home page
- About/Resume page
- A professional projects page
- A contact form



## 5. About
Made by Jeremie Faye using code provided by Udacity

