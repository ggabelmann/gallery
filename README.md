gallery
=======

Gallery is a simple client-side-only web app written in CoffeeScript which uses backbone.js to view photos.

Usage
=====

Download the source code (either using git or else the available zip) and serve it using any web server. I switch to the folder above src/ and run:

webfsd -4 -F -R .

Then I open a new browser window and go to (for example):

http://localhost:8000/src/gallery.html?json=../example/desktops.json

gallery has relative links to the libraries it needs so all it needs from the user is the location of the json file.

Future
======

Documentation.

Unit tests.

Auto-sizing of photos.

Styling.
