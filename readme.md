Gulp-Ionic-Browserify Boilerlate
=================================

## Tools Prerequisites
* Node.js platform, installing [Node.js](http://www.nodejs.org/download/)
* Gulp - The streaming build system, installing [Gulp](http://gulpjs.com/)
* Bower - Web package manager, installing [Bower](http://bower.io/)

## Why?

This repository is intended to provide as base structure for starting 
and working with a Ionic application. It uses AngularJS as an application 
framework and Browserify is used to compile the application into a single 
bundle. 

## What do we get!?

### Code Structure
Using EditorConfig, Lintspaces, and JSHint enforces better code quality and 
ensures higher standards. Keep them included and be stringent!

### Manging Cordova Correctly
Many Cordova projects I've worked on assume you have Cordova installed globally 
and will use that to do builds causing a major headache due to version 
mismatches. Building should be accomplished by using a localised Cordova 
version installed as part of the project and as a result this project has a 
relative symbolic link setup to accomplish this. Simply use _./cordova_ in the 
root of this project to perform all Cordova tasks as this will use the version 
installed locally in the _node_modules_ folder.

