node-http-server-boilerplate
============================

A simple boilerplate for serving up a site using Nodeapps/Nodejitsu's http-server

##Getting started
Download/clone this repo, then run

	npm install

Now you can test it out by running

	npm start

##Configuration
You can change the path from where it serves files; by default it runs from the directory called in the CLI and looks for ./public but if you want to change it open up ./bin/server and change

	serveFrom = /your/new/path/here