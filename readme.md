# Super Simple Server

This is a super, super simple web server. It will serve up your index.html file. 

## To Run Locally

     node app.js

     Open your web browser to localhost:3000

## To deploy to heroku

     Go to heroku.com and create a free account. You'll need a valid email address.

     In your folder where you have your index.html file type:

     heroku login

     heroku create your-app-name

     git push heroku master

     heroku ps:scale web=1

     heroku open


