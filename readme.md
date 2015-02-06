# JL Gulp Starter

JL Gulp starter is my current personal font-end framework using gulp, node, compass, susy, breakpoint, browser-sync, autoprefixer and uglify.

Since this framework requires Compass you must have Ruby compass, susy and breakpoint install on your system.  I hope to remove this dependency in the near future.

## Start

After cloning the project you can download all the depend node module using

	npm install


## Build

Create a deployment build with the following commands

	gulp build
	gulp remove

'Gulp build' moves all the files from your 'app' folder into a build folder.  'Gulp remove' removes any files that you do not want in you deployment.  These files can be configured as an array in the 'gulpfile.js' file.
