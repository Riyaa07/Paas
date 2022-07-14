# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

# STEPS

1. Open Github Desktop
    i. Create a new repository 
    ii. it contains the git attributes
    ii. Named it as  Paas
    iii. Push to origin
    iv. Place the Pass Code inside that repositoy and commit to main.

2. Create an Heroku Account
    i. Open this link- https://dashboard.heroku.com
    ii. Sign up with college email id
    iii. Select the langugage to be Ruby.

3. Make New App
    i. Verfying the email
    ii. Create new app
    iii. Give any name of your choice I gave it - deployment-web
    iv - Dont do anything in add piple simply click the create button

4. Link To Github
    i. Give authorized access of Github to heroku
    ii. Connect the repoistory
    iii. Provide the name of your repository and search it

5. Deployment
    i. Enable the Automatic Deploy
    ii. Click on deploy branch
    iii. After deploying click on Resources form Navigation
    iv. Inside that click on open app

This will give some kinds of error that something went wrong it is beacuse of the ruby configuration

6. Configure
    i. In that resouces there will be an more button
    ii. Inside more button click on run console

7. In run console run the following command
    i. bundle install
    ii. rails server
    iii. rails db:migrate
    iv. rails db:seed

8. After running this commands now your app will be live on heroku server

   https://deployment-web.herokuapp.com

   i. You will need to sign up
   ii. Now you can see that 50 articles and 10 comments on each are seeded.
