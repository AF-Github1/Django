# Django (IN PROGRESS)

This document shall handle what I have learned as I followed through the tutorial provived at the main Django site. 

It will serve as a much more general guide to what I specifically did/handle while learning Django. If you wish to learn Django yourself, you will be better served by following their own tutorial at their own site

**https://docs.djangoproject.com/en/4.2/**

This process was done on a Windows machine

# Booting up current install


**cd C:\'Program Files'\learning\mysite**

Change learning and mysite according to where you have your virtual env directory and site root directory

**py manage.py runserver**

Copying code without spaces

Use this command

**cp file.ext C:\Users\Username\'OneDrive'\'Desktop'\name.txt**

Where file.ext, is the file whose code you want to copy and nome.txt the file with the name you want to create. Just remember you will need to be in the same location to copy the file or be precise to indicate where it should go.
Change the names on the path as needed.

# Quick install guide | Django documentation

1- Install Python's most recent version 

2- Go to path where you want to make a new folder

3- Make it in the directory you want to put it at

**py -m venv learning**

4- Current name/path for mine

**C:\Program Files\learning**

5- Then activate the env

**learning\Scripts\activate.bat**

6- And install django in it

**py -m pip install Django**

7- Install Git for Windows

8- Fix the installation if need be. Check link below

https://stackoverflow.com/a/34767523/7278024

Remember to restart cmd

9- Git should be working now. Use these commands to finish it up

**git clone https://github.com/django/django.git**

**py -m pip install -e django/**



10-

Enter the created directory, in my case I enter the learning directory

Now you can start.Tutorial indications might not be completely right, you have to use py with django command if you are on a windows machine.

For example to start the site:

**py -m django startproject mysite**

This creates the root directory for the site in your learning folder

And finally, to boot it up go to the root directory and use

**py manage.py runserver**

By checking your local host you can see if you did it properly

![image](https://github.com/AF-Github1/Django/assets/133685290/48429a6b-77af-47e1-b9d3-659c79bfa71c)

![image](https://github.com/AF-Github1/Django/assets/133685290/4ec9e10c-afe6-4c14-9952-c2244a48269d)









