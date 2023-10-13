# pronto_test

This is a Rails 6 app.

## Prerequisites

This project requires:

* Ruby 2.7.5
* PostgreSQL must be installed or docker container running and accepting connections

## Getting started

Create `.env` from `env.example` and populate the variables.
Run the `bin/setup` script, which will:

* Install dependencies using Bundler
* Create and migrate database

### Run it!

1. Run `bundle exec rake factory_bot:lint` to check if all factories are working.
2. Run `bundle exec rspec` to run all the tests
3. Run `rails s -b 0.0.0.0` to start the web application