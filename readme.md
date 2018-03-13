# Performance Checklist

## Table of Contents

*   [Miscellaneous](#miscellaneous)
*   [Audits](#audits)
*   [HTTP optimisation](#http-optimisation)
    *   [HTTP/1](#http1)
    *   [HTTP/2](#http2)
*   [Caching](#caching)
*   [Minification](#minification)
    *   [Images](#images)
    *   [CSS](#css)
    *   [HTML](#html)
    *   [JavaScript](#javascript)
    *   [Fonts](#fonts)
*   [Perceived Performance](#perceived-performance)
*   [Performance](#performance)
    *   [Images](#images-1)
    *   [CSS](#css-1)
    *   [HTML](#html-1)
    *   [JavaScript](#javascript-1)
    *   [Fonts](#fonts-1)
*   [Backend optimisation](#backend-optimisation)

## Miscellaneous

*   Tip: Different profile / user in Chrome without extensions
*   Add some more points here...

## Audits

*   Add some more points here...

## HTTP optimisation

*   Currently the SSL certificate is only being activated on the main page www.cmd-amsterdam.nl . To activate the SSL certificate on all the other pages there may not be any conflicting http references. Currently the images have an http reference instead of an https reference. To change all the images to https, all images should be reuploaded to the Wordpress image library while the Wordpress website itself is set to https. All images on the pages should be replaced with the right images whith an https reference. 

While an SSL certificate does not directly influence page load speed, it does come up in speed insight tests and results in a lowered overall score. It also provides visitors of the website with a sense of security, and it also makes the website in general more professional. 

example of an image on the https://www.cmd-amsterdam.nl/cmd/ page with an http reference:
http://www.cmd-amsterdam.nl/wp-content/uploads/2013/11/cmd-core-nl.png

For sources and detailed info, check out:
https://premium.wpmudev.org/blog/replacing-image-links/
https://www.inmotionhosting.com/support/website/wordpress/enable-https


### HTTP/1

*   Add some more points here...

### HTTP/2

*   Add some more points here...

## Caching

*   Add some more points here...

## Minification

*   Add some more points here...

### Images

*   Add some more points here...

### CSS

*   Add some more points here...

### HTML

*   Add some more points here...

### JavaScript

*   Add some more points here...

### Fonts

*   Add some more points here...

## Perceived Performance

*   Add some more points here...

## Performance

*   Add some more points here...

### Images

*   Add some more points here...

### CSS

*   Add some more points here...

### HTML

*   Add some more points here...

### JavaScript

*   Add some more points here...

### Fonts

*   Add some more points here...

## Backend optimisation

*   Add some more points here...
