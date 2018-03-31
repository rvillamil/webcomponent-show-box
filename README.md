# Webcomponent: show-box

Vanilla Web component to display covers and other info, about films or tvshows.

## Using

You can [download the latest release](https://github.com/rvillamil/webcomponent-show-box/releases) for your operating system or build it yourself (see below).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You'll need [Node.js](https://nodejs.org/es/) installed on your computer in order to build this library.

First step

```sh
$git clone https://github.com/rvillamil/webcomponent-show-box
$cd webcomponent-show-box
```

Second step

```sh
$npm install http-server -g
cd examples
$http-server
```

### Example use

```html
<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>ShowBox - Webcomponent Sample</title>
    <link rel="import" href="show-box.html">
    <link rel="import" href="tvshow-link.html">
</head>

<body>
   <div>
        <show-box title="Modern Family" originaltitle="Modern family" quality="HDTV 720p" releasedate="12-10-2003" urltodownload="http://tumejorjuego.com/redirect/index.php?link=descargar-torrent/100089_modern-family-temporada-9-hdtv-720p-cap-903-ac3-5-1-espaa-a-ol-castellano/"
            urlwithcover="http://localhost:8080/Logo_IMDB.png" imdbrating="6.3" rottentomatoes="50/10">
            <tvshow-link session="1" episode="6" urltodownload="http://tumejorjuego.com/redirect/index.php?link=descargar-torrent/100089_modern-family-temporada-9-hdtv-720p-cap-903-ac3-5-1-espaa-a-ol-castellano/"></tvshow-link>
            <tvshow-link session="2" episode="8" urltodownload="http://tumejorjuego.com/redirect/index.php?link=descargar-torrent/100089_modern-family-temporada-9-hdtv-720p-cap-903-ac3-5-1-espaa-a-ol-castellano/"></tvshow-link>
        </show-box>
    </div>

    <div>
        <show-box title="Depredador" originaltitle="Predator" size="5.4Gb " quality="HDTV 720p" releasedate="12-10-2003"
            urltodownload="http://tumejorjuego.com/redirect/index.php?link=descargar-torrent/100089_modern-family-temporada-9-hdtv-720p-cap-903-ac3-5-1-espaa-a-ol-castellano/"
            urlwithcover="http://localhost:8080/Logo_IMDB.png" imdbrating="6.3" rottentomatoes="50/10" tmdbrating="7.1" />
    </div>
  </body>
</html>
```

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/rvillamil/vws-js-app/tags).

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
