# racket-sample-heroku-app
a sample Racket application for deployment to Heroku

Usage
-----

Example usage:

    $ heroku create --buildpack https://github.com/a-nano/heroku-buildpack-racket.git
    
    $ heroku config:set RACKET_VERSION=current

    $ git push heroku master
