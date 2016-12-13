**Forked from [PlexRedirect] (https://github.com/ITRav4/PlexRedirect)**

# PlexRedirect
a Plex landing page that redirects you to various sites.
![alt tag](http://i.imgur.com/pilOWJH.png)
![alt tag](http://i.imgur.com/rmFjRyC.png)

## Features:
* Link to [Plex.tv](plex.tv)
* Link to [PlexRequests](https://github.com/lokenx/plexrequests-meteor)
* Link to [PlexPy](https://github.com/JonnyWong16/plexpy)
* Link to server stats
* Shows Plex status (online or offline) using [ping.js](https://github.com/alfg/ping.js)
* Centralized configuration in config.php
* Shows currently streaming to number
* Donation via PayPal
* Vector graphics
* Fullcalendar.io integration

## Contributors:
[@EldonMcGuinness](https://github.com/EldonMcGuinness): Added ping.js to the code so the website now checks the server status automatically.

[@lienma](https://github.com/lienma): Fixed Google fonts so it now chooses between https and http.

I have used some of [@gruppler](https://github.com/gruppler)'s PHP code in his version of PlexRedirect

## Installing:
Add this to your webserver root folder. You can rename it to your server name if you would like. Access it via your IP address. PHP is needed to run.


## How I installed it:
The way I have it set up is forwarded my domain with masking to my public IP address and port. 

Ex: www.example.com points to x.x.x.x:xxxx/PlexRedirect. I then have a subdomain for PlexRequests (requests.example.com) which then forwards it to my public IP address and port x.x.x.x:1001 with masking. I did the same for the PlexEmail site (right now it takes you to a "Coming Soon" website since I haven't set up PlexEmail yet.) Clicking on the "Access Server," "Request," and "What's New" redirects you to those addresses.

## License
Licensed under The MIT License. The Plex logo and name are copyright of Plex Inc.
