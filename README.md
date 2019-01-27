# Andy Felder Website

[![Build Status](https://travis-ci.com/andyfelder/andyfelder.github.io.svg?branch=master)](https://travis-ci.com/andyfelder/andyfelder.github.io)

Website for [Andrew Felder](https://andyfelder.github.io)


## Editing content

All pages on the website are written in Markdown (specifically
[Kramdown](https://kramdown.gettalong.org/quickref.html)). For a Markdown
reference, see here:
[https://www.markdownguide.org/basic-syntax/](https://www.markdownguide.org/basic-syntax/)

The important folders are `images/` and `pages/`. Upload pictures to the
`images/` folder and edit webpages in the `pages/` folder. Within `pages/`,
`index.md` is the home page for the website. Each of the other files are
sub-pages linked to in the navigation banner. Don't worry about the contents
of `pages-root-folder/`, they shouldn't need to be modified.

To edit a file on github:

1. Check that you are logged in on Github
2. Click on the particular page that you want to edit
3. Click the pencil ("Edit this file") to begin editing
4. Make changes!
5. When you are done, click the green "Commit changes" button at the bottom of the screen to save changes
6. Check on [the website](andyfelder.github.io) that everything still looks good on the page you edited


## Building locally

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

