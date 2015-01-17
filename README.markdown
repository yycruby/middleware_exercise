RACK MIDDLEWARE EXERCISE
========================

This is a simple exercise to learn about writing Rack Middleware. The goal is
write three pieces of middleware to do three separate tasks:

  - Rescue and handle exceptions
  - Authorize requests with HTTP header
  - Handle JSONP formatted requests

The exercise will provide you with an existing environment, so you only need to
worry about the work that the middleware does. This repo includes some light
tests to guide your development.

To get started, fork this repo and open a pull request. When you think you have
a solution to one of the required middlewares, you can push up a commit. The
automated test runner will (hopefully) be notified and run the tests against
your repo.

Getting started:
----------------

Clone the repo:

    git clone git@github.com:timuruski/rack_middleware_exercise.git

Install necessary gems:

    bundle install

Run the tests:

    rake test
