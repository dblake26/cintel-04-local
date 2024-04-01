# README for Module P4 - cintel-04-local

## Project Title

Publish Interactive Reactive App

## Project Description

This project will much more closely follow the typical workflow of a real interactive development project. In Module 4, we create a repo in GitHub, clone it down, create a local project virtual environment in the .venv folder, activate our .venv virtual environment, and install all the packages we need.

Once the project virtual environment has everything required, we can open the project folder in VS Code, open a terminal, activate the project virtual environment (so we have access to the packages we installed into .venv), and run our app. We edit and rerun as often as needed - remember to activate your project virtual environment each time you work on the project. 

Focus: The focus in this course is on designing and implementing Interactive Apps - not the local Python development details or even the tools. For now, just follow each step carefully - you'll learn more in 44-608 Data Fundamentals and apply this process in other courses. Trust that by the time you graduate, it will be familiar.  Use your README.md to keep notes. 

# Notes for Project

## Following the recommended workflow

You started with the repo in GitHub and cloned it to your local machine. 

You created a local project virtual environment in the .venv folder, activated it, and installed necessary packages. 
  packages include 
  py -m pip install --upgrade pip setuptools

py -m pip install --upgrade -r requirements.txt

After all that, you should be able to open your project folder (cintel-04-local) in VS Code.

Open a terminal and activate the project (anytime you open a new terminal) and run the shiny app.

shiny run --reload --launch-browser penguins/app.py

While the app is running, that terminal is fully occupied.

Open a new terminal to run other commands.

## Commands 
- With your project virtual environment active in the terminal and the necessary packages installed, run the app with live reloading and automatically open it in the browser:

shiny run --reload --launch-browser penguins/app.py

- What command creates the virtual environment?
python -m venv .env

- What command activates the virtual environment?
  .env\Scripts\activate
  
- What command installs pip, setuptools, and wheel packages into the virtual environment?
  pip install -U pip setuptools wheel
  
- What command installs spacy into the virtual environment?
  pip install -U spacy
  
- What command downloads and installs the spaCy model en_core_web_sm (English core small model).
  python -m spacy download en_core_web_sm
