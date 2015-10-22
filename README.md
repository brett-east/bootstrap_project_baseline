#README file
_This baseline was based on the [Lynda.com](http://www.lynda.com) project [Web Project Workflows with Gulp.js, Git, and Browserify](http://www.lynda.com/Web-Design-tutorials/Web-Project-Workflows-Gulp-js-Git-Browserify/154416-2.html) by [Ray Villalobos](https://github.com/planetoftheweb)._

##Bootstrap Project Baseline

###Description

This repository contains a baseline project setup for Bootstrap projects. It uses Sass for styling and includes bootstrap.css, as well as jquery-1.11.3.min.js and bootstrap.min.js.

###package.json dependencies

This base project has devDependencies for the following npm node modules. Node modules are not included within this repository and will need to be downloaded as dependencies in the terminal by running `npm install`.

* "gulp": "^3.8.11"
* "gulp-compass": "^2.0.3"
* "gulp-concat": "^2.5.2"
* "gulp-connect": "^2.2.0"
* "gulp-if": "^1.2.5"
* "gulp-imagemin": "^2.3.0"
* "gulp-jsonminify": "^1.0.0"
* "gulp-minify-html": "^1.0.0"
* "gulp-uglify": "^1.1.0"
* "gulp-util": "^3.0.4"
* "imagemin-pngcrush": "^4.0.0"

###Gulp default command

After installing the dependencies, running `gulp` in the terminal will call a number of gulp functions for the **_development_** environment. These functions will watch for changes in js, scss, image and html files, and then concatenate them into smaller files that are referenced in the html. This will also start a server and reload the browser window.

To run gulp for the **_production_** environment, run `NODE_ENV=production gulp`, this will package up files and minify them, as well as compressing images for production.