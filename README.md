About
====

Photo Hack Day 4 project, http://letsgo.io (2013)

We used new technologies to build a great experience within 24 hours of hacking.
We used many APIs and Data Sciences to find the most interesting beautiful photos
to show you from any location to some destination.

It renders the best possible directions and around those directions it places
photo pins to showcase the beautiful interesting spots around that area. You
can alter your trip so you can visit that one place.

Team Members
============

* Jeremy Benaim [@jeremybenaim](http://github.com/jeremybenaim)
* Joey Hiller [@jthiller](http://github.com/jthiller)
* Justin Ormont [@justinormont](http://github.com/justinormont)
* Ray S [@ray-s](http://github.com/ray-s)
* Mohamed Mansour [@mohamedmansour](http://github.com/mohamedmansour)

Technologies Used
=================

* Node.js (express, passport, request, nconf, ejs, azure)
* Windows Azure (Cloud Storage and Cloud Services)
* Bing Maps API (for waypoints, directions, pins, geolocation lookup)
* Flickr API (For images and their locations)
* HTML5 (transitions, animations, media queries)

How to Install
==============

1. Make sure you clone this repo
2. Copy config.json.defaults to config_development.json and fill in your API keys
3. Run "npm install" from the root project directory
4. Then just run node "npm start" from the root
5. Visit http://localhost:3000 to allow OAuth with Facebook to work, just update your hosts to point letsgo.io to localhost and just visit http://letsgo.io:3000

Please submit pull requests so we can make this project more awesome :)
