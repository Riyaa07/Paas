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
    * Create a new repository 
    * it contains the git attributes
    * Named it as  Paas
    * Push to origin
    * Place the Pass Code inside that repositoy and commit to main.

2. Create an Heroku Account
    * Open this link- https://dashboard.heroku.com
    * Sign up with college email id
    * Select the langugage to be Ruby.

3. Make New App
    * Verfying the email
    * Create new app
    * Give any name of your choice I gave it - deployment-web
    * Dont do anything in add piple simply click the create button

4. Link To Github
    * Give authorized access of Github to heroku
    * Connect the repoistory
    * Provide the name of your repository and search it

5. Deployment
    * Enable the Automatic Deploy
    * Click on deploy branch
    * After deploying click on Resources form Navigation
    * Inside that click on open app

This will give some kinds of error that something went wrong it is beacuse of the ruby configuration

6. Configure
    * In that resouces there will be an more button
    * Inside more button click on run console

7. In run console run the following command
    * bundle install
    * rails server
    * rails db:migrate
    * rails db:seed

8. After running this commands now your app will be live on heroku server

 *  https://deployment-web.herokuapp.com

   * You will need to sign up
   * Now you can see that 50 articles and 10 comments on each are seeded.
