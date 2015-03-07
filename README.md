# MJPEG-SS-WEBUI
#Current version 0.3 (in development)
MJPEG-SS-WEBUI is a lightweight, cross-platform MJPEG web user interface for surveillance systems (and other MJPEG streams).

At the present day there are many video devices that save in MJPEG format (for more information about [MJPEG](http://en.wikipedia.org/wiki/Motion_JPEG) ). Many of them are security systems that record camera streams and want to provide a low load, cheap and flexible service. I'm sure it's also possible to convert other video formats to MJPEG.

This project aim to create the most lightweight and portable software of MJPEG streaming, HTML 5 and CSS3 compliant.

The MJPEG stream do not need to be on the same host as the MJPEG installation.

It will NEVER need any SQL database for any purpose.

It supports SSL/TLS encryption with HTTPS.

Authentication (Apache authentication modes only for now) 

Configuration can be done by web-ui or changing 2 files (main + one each camera).

Works with [motion] (http://www.lavrsen.dk/foswiki/bin/view/Motion/WebHome)

#### TO DO
- Multilanguage
- Configuration web-ui
- Style rework and customization
- Authentication mechanism
- User friendly custom stream name configuratino

###0.3 7/03/2015
- HTTPS support (henceforth SSL)
- Non standard port support

### 0.2 7/03/2015
- CSS added (to improve further)
- Multiple cameras support
- Basic playback controls

### 0.1 6/03/2015
- Display MJPEG stream

# Requirements
- Server
- PHP 4.x
- MJPEG "stream"

Client
- Javascript enabled browser

# Browser Compatibility
Google Chrome (any platform)
Mozilla Firefox (any platform)
Others (to test)
