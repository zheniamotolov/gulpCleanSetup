# JL Gulp Starter

JL Gulp starter is my current personal font-end framework using Gulp, Node, Compass, Susy, Breakpoint, Browser-Sync, Autoprefixer and Uglify.

Since this framework requires Compass you must have Ruby Compass, Susy and Breakpoint install on your system.  I hope to remove these dependency in the near future.

## Start

After cloning the project you can download all the depend node modules using:

	npm install


## Build

Create a deployment build with the following commands:

	gulp build
	gulp remove

'Gulp build' moves all the files from your 'app' folder into a build folder.  'Gulp remove' removes any files that you do not want in your deployment.  These files can be configured as an array in the 'gulpfile.js' file.
