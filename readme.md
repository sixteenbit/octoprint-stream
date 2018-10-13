# OctoPrint Stream

Simple landing page to show your webstream.

## How to

1. `cd ~/mjpg-streamer/www-octopi`
1. `sudo wget -N https://raw.githubusercontent.com/sixteenbit/octoprint-stream/master/index.html`
1. [octopi:8080](http://octopi:8080) will load locally. Point your domain to your pi's local IP and forward port 8080

## Custom themes

Since Bootstrap is being used, you can edit the main stylesheet on `line 9` of the index.html to use any of the 
themes from [Bootswatch](https://www.bootstrapcdn.com/bootswatch/).

### Example

If you're wanting to use the Cyborg theme, replace the following:

```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
```

With:

```html
<link href="https://stackpath.bootstrapcdn.com/bootswatch/4.1.3/cyborg/bootstrap.min.css" rel="stylesheet" integrity="sha384-4DAPMwiyOJv/C/LvTiUsW5ueiD7EsaAhwUKO0Llp+fWzT40XrmAbayhVP00bAJVa" crossorigin="anonymous">
```

Be sure to review the theme you choose since it comes with different styles for the navbar. By default, `navbar-dark bg-primary` is set, but you may want to change it for a different color.