My-secure-chat
  This app allowed user to sign in and sign up. Once they are inside the app they can create the chat channels and message each other and the can upload the picture to shared each other. I used API to create Admin login to controlled my app.

Getting Started
  Deployed: https://mysecurechat.herokuapp.com/users/sign_in

Requirements
  Require ruby version 2.5.0 to be installed to use. For admin login I used ruby framework to make admin login though API.

Installing

Dependencies must be installed to work properly.

Getting started with bundler is easy.

Open a terminal window and run this command:
  gem install bundler

Specify your dependencies in a Gemfile in your project's root:
  source 'https://rubygems.org'
  gem 'nokogiri'
  gem 'rack', '~> 2.0.1'
  gem 'rspec'

Install all of the required gems from your specified sources:
  bundle install
  git add Gemfile Gemfile.lock

Usage
  Users need to sign up for the app to use. Once sign up/logged in, users will able to used the app and they can chat each other.

Running the tests using teriminal
  bin/rails test -b test/models/article_test.rb

Credit
  This app used Ruby on Rails framwork to create API to collection data form the app.

Author
  Puspa Khanal
