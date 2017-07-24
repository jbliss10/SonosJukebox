# SonosJukebox

First, install https://github.com/jishi/node-sonos-http-api/ and start node server (it is automatically configured to run on port 5005).

Replace any references in SonosJukebox IP host to your own localhost or domain that will be hosting the page.  

Replace the room "kitchen" with any default Sonos room.  Eventually I'll update the code to abstract that to a constant or settings file or not require a default room and let the user pick it from the screen.

If nothing is loading see Jishi documentation to ensure it is set up successfully, try hitting http://yourip:5005/zones and see if it displays all your Sonos rooms correctly in the JSON response.
