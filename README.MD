# Bolt Starter theme with bourbon, neat, and bitters

This is a starter theme based on HTML5Boilerplate v4.3.0, with sass libraries bourbon, neat, and bitters. A clean and solid base for your bolt theme.

## Setting-up

### Set-up gulp:
Gulp is used to compile the scss

#### Create package.json:
	$ npm init
#### Install gulp and gulp-ruby-sass:
	$ npm install gulp --save-dev
	$ npm install gulp-ruby-sass --dave-dev

=====

### Install bourbon and neat in scss directory:

#### Install gems if not already installed:
	$ gem install bourbon
	$ gem install neat
	$ gem install bitters

#### Install bourbon and neat into scss directory:
	$ cd scss
	$ bourbon install
	$ neat install
	$ bitters install

=====

Gulp should now be installed and hooked-up correctly within `gulpfile.js`. You can test it by putting something in `scss/app.scss` and compiling it with:

	$ cd ..
	$ gulp sass

If everything's hooked-up then this change should be relfected in the `css/app.css` file.


