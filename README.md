1.Create a directory and copy the project files at the location
2.Depending on OS , set environment variable for project directory from where the Flask Application will run. 
3.Please refer commands below for setting environment variable on windows machine. In below example LocalAuthWebServer is the name of directory in which all the files are located. So, below commands need to be run on wondows command line at one folder level above "LocalAuthWebServer" and NOT inside of "LocalAuthWebServer". This is important, or else the Flask application will not run successfully
    * SET FLASK_APP=LocalAuthWebServer
    * SET FLASK_DEBUG=1 
4.All the user data and DB structure is part of SQLITE DB 
5.Please ensure all the dependencies are installed i.e. flask, flask_login, flask_sqlalchemy,flask_login
