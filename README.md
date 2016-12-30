# Trello Power-Up On Heroku

This is a sample [Power-Up](https://developers.trello.com/power-ups/intro) built for the Trello platform and intended to be hosted on Heroku.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/trello/power-up-on-heroku&env[PORT]=80)

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```sh
$ git clone git@github.com:trello/power-up-on-heroku.git # or clone your own fork
$ cd power-up-on-heroku
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying via Heroku CLI

Ensure that you have [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) installed. 

```
$ heroku create
$ git push heroku master
$ heroku open
```

