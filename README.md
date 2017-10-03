# README

## Background

This boilerplate uses the most recent release of Rails (as of 09/2017, 5.1.4). It also takes advantage of the Webpacker gem to integrate React ([link to gem](https://github.com/rails/webpacker)). Reasons for this can be found on my blog (link to come). As a bonus, the React testing environment is also set up for you, using Jasmine/Enzyme with PhantomJS. To set up this testing environment, I used this gist from my friend ([link to gist](https://gist.github.com/andrewprogers/65f0228c262fbe8e1efe767527540aec)).

## How-to

* Clone down this repo to your desktop and rename as necessary.
* Run `bundle` and `npm install` to get all the dependencies sorted out.
* Run `rake db:create` to set up your database properly.
* Before testing with React, you will need to add the location of your `testHelper.js` to the `karma.conf.js` file. To do this, navigate to `karma.conf.js` and paste the `testHelper.js` file path into the `files` array (I've also left a comment and an example there for you). It is also possible that you will need to run `karma init`. You can answer the questions from the prompt using [this gist](https://gist.github.com/andrewprogers/65f0228c262fbe8e1efe767527540aec).
* When you want to run the servers to see your work locally, run both `rails s` and `npm start` (separate tabs in the same project folder).
* When you want to check your React tests, run `npm test`. (Run `rake` for Rails/Ruby tests.)


## Notes

* The Webpacker gem comes with its own example that gets set up when you download it. You can read about how to connect the example to your work to troubleshoot the environment.
* As with any environment, not everything is going to be perfect. Please leave comments or questions for me, and I'd be happy to answer. This is a work in progress, and I'll likely be adding "dummy" components/pages for people to see how Webpacker interacts in a Rails environment.
