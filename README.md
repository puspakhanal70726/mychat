# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
2.5.0

* System dependencies
 Bundler, a popular gem management tool. Bundler can help to resolve dependencies when working with Ruby gems by allowing you to specify a set of gems in a Gemfile, then issue a single command to install them.

* Configuration
Software is designed with default behavior built in, so some specific configuration is usually required before the software works (like a path to reach a dependency), or a default and possibly rudimentary implementation may run without it.

* Database creation
Migrations are Ruby classes that are designed to make it simple to create and modify database tables. Rails uses rake commands to run migrations, and it's possible to undo a migration after it's been applied to database.

* Database initialization
first I used sqlLite3 database but to deploy in Heroku have to change sqlLite3 into Postgress.

* How to run the test suite
The Three Environments
production
development
test


* Services (job queues, cache servers, search engines, etc.)
app
|- actions
|- assets
|- controllers
|- decorators
|- models
|- policies
|- services
|- support
|- views

* Deployment instructions in Heroku
Deploying code. To deploy app to Heroku, you typically use the git push command to push the code from  local repository's master branch to heroku remote, like so: $ git push heroku master Initializing repository, done.

* ...
