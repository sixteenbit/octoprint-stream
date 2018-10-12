# OctoPrint Stream

Simple landing page to show your webstream.

## How to

1. `cd ~/mjpg-streamer/www-octopi`
1. `sudo rm index.html`
1. `sudo wget https://raw.githubusercontent.com/sixteenbit/octoprint-stream/master/index.html`
1. [octopi:8080](http://octopi:8080) will load locally. Point your domain to your pi's local IP and forward port 8080

## Custom Bootswatch themes

Since Bootstrap is being used, you can edit the main stylesheet on `line 9` of the index.html to use any of the 
themes from [Bootswatch](https://bootswatch.com/).