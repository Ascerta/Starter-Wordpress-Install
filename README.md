Wordpress starter install
=============

We use this as the base install for most of our Wordpress projects. There's not much to it.
The main changes are in wp-config.php there's a switch statement so database info can be added for dev, staging and deployment servers.
There's also the starter theme with boilerplate function and css files.

*****Security warning******* 
searchreplacedb2.php is included which allows you to change the Wordpress base url as well as updating all referenced in the DB. Do not put this 
on your live or publicly accessibly server as it could be a huge security hole. 