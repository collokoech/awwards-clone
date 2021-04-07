# PROJECT NAME
## awwards-clone

## AUTHOR
* Collins Cheruiyot Koech

## DESCRIPTION
The application will allow a user to post a project he/she has created and get it reviewed by his/her peers.

## BEHAVIOUR DRIVEN DEVELOPMENT

* The user must sign in to be able to post projects and review projects for others users.



## FEATURES

--View posted projects and their details
--Post a project to be rated/reviewed
--Rate/ review other users' projects
--Search for projects 
--View projects overall score
--View my profile page

## SETUP INSTALLATION

1.Clone or download and unzip the repository from github,https://github.com/collokoech/awwards-clone.git

2.Activate virtual environment using python3.8 as default handler virtualenv -p /usr/bin/python3.8 venv && source venv/bin/activate

3.Install dependancies that will create an environment for the app to run pip3 install -r requirements.txt

4.Create the Database

* psql
* CREATE DATABASE instacopy;
5.Create .env file and paste paste the following filling where appropriate:
-SECRET_KEY = '<Secret_key>' 
-DBNAME = 'Awwards' -USER = ''
 -PASSWORD = '' 
 -DEBUG = True
6.  Run initial Migration 
    -python3 manage.py makemigrations instagram 
    -python3 manage.py migrate .Run the app 
    -python3 manage.py runserver 
    -Open terminal on localhost:8000

## TECHNOLOGIES USED
* Python 3.8
* Bootstrap
* HTML/CSS
* Postgre sql



## LICENSE
The project is under[MIT license](/blob/master/LICENSE)
Copyright @2021.Collokoech
  
