# Jekyll with Gulp Boilerplate

So, this is a totally opinionated skeleton to get a Jekyll site up and running quickly.

## Components

This thing uses:

* Jekyll
* Gulp
* Browsersync
* Sass
* Normalize
* Stylelint

## Setting up

1. Install bundler (`gem install bundler`)
2. Install gems with `bundle install`
3. Get all the needed node modules with `npm install`

## Developing

Fire the whole thing up: `gulp` (Google Chrome opens, everythings waiting for you to change `.md`, `.html`, `.scss`, etc etc and will auto reload everything).

### Stylelint

To ensure consistency in CSS code, I added Stylelint to this project. Linting is gonna take place directly while developing (when you run gulp) or also in the Gitlab CI test job later on.

## Building

Run `gulp build:staging` to build to project out to a directory called `public`.
