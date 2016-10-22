# Web Development Group
This is the part of the project for the front end web developement. Our goal is to make a website that allows users to submit and retrieve information from the database. This README will explain how to set it up on your computer.

## Installing the required applications

* ###  Python 
    1. https://www.python.org/downloads/
    2. Download version 3.5.2
    3. Install
    4. Check your python version by opening Command Prompt (Windows) or Terminal (Mac/Linux) and executing the command `python --version`  
    If it's not *Python 3.5.2*, then you may have had a previous version of Python installed. The new version might be ran with `python3`, or `python352`. In which case, all references to python executions should use that.

* ### Django 1.10.2
    Before you start, check your python version with 
    * Windows
        1. Open Command Prompt as Administrator
        2. Run `python -m pip install Django==1.10.2`
    * Mac/Linux
        1. Open the Terminal
        2. Input `sudo python -m pip install Django==1.10.2`


* ### Jetbrains Pycharm 
    1. https://www.jetbrains.com/pycharm/download/
    2. Download the Community Edition

 * ### Github Desktop Program (optional)
    1. https://desktop.github.com/

## Downloading from Github

Download the `Web` branch from https://github.com/CCSF-Coders/ClubFinder.git  
You can either use the desktop program to download it, download it from the website, or use the Git CLI.

## Setting up and running the server locally
In Pycharm, open the Web folder for the project you downloaded off Github.

* ## Settings
    The Project Settings, which you can access via `File > Settings`, should be already set properly. You should check the following anyway:

    * **Project: Web** > Project Interpreter  
    This should be set to 3.5.2. If it's not click the dropdown and set it to 3.5.2  
    The Package list should also have Django in there. If it's not there, then Django wasn't installed properly.
    
    * **Languages & Frameworks** > Django  
        * Django Project Support ☑
        * Django Project Root: *where you saved the repository*\ClubFinder\Web\front_end
        * Settings: front_end\settings.py
        * Manage Script: manage.py
        
 * ## Starting/Stopping the server
    Please note when you start the server, it will continue to run even when you close Pycharm.
    * Go to `Tools > Run manage.py Task...` 
    * In the console:
        * Type and execute`runserver` to start it.
        * Click the Stop button in the console to stop it.
    * Click on the URL (usually http://127.0.0.1:8000/) in the console, or copy and paste it to your web browser.

Congratulations! If you were able to view a web page of some sort, then you have successfully set up your project and are ready for development.