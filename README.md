# Andy Felder Website

[![Build Status](https://travis-ci.com/andyfelder/andyfelder.github.io.svg?branch=master)](https://travis-ci.org/andyfelder/andyfelder.github.io)

Website for [Andrew Felder](https://andyfelder.github.io)

## Building

Dependencies:

First install ruby and ruby bundler if you don't already have it from another ruby project:

    sudo apt install ruby ruby-dev
    gem install jekyll bundler

or

    # Note: No sudo on a Mac. You should never use sudo for these kinds of installs on a Mac anymore.
    # sudo may make this work for now, but it will make your life miserable in the long run.
    brew install ruby
    gem install jekyll bundler

Then use bundler to install the needed gems

    bundle install

To build the website:

    bundle exec jekyll serve

Now browse to http://localhost:4000 to view

