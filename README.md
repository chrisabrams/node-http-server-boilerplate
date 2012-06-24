node-http-server-boilerplate
============================

A simple boilerplate for serving up a site using Nodeapps/Nodejitsu's http-server

##Usage
For when you just need a static site and want to use a node module to serve the static files on a server.

##Getting started
Download/clone this repo, then run

	npm install

Now you can start the server by running

	npm start

##Configuration
You can change the path from where it serves files; by default it runs from the directory called in the CLI and looks for ./public  
  
If you want to change the loading path, open up ./bin/server and change

	serveFrom = /your/new/path/here

If you want to change the port, just change

	servePort = 