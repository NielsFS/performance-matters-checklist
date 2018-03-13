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

*   Add some more points here...

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

*   See below as it applies to both performance nd perceived performance

## Performance

*   Critical css makes the page only render css "above the fold". Everything that is not in browser view is being styled by CSS after the content that is "above the fold" and in browser view. On the website voorhoede.nl they explain that creating your own critical css path is very time consuming. Therefore it is advised to use reliable readymade scripts to make your website perform better. One example that De Voorhoede uses is: https://github.com/addyosmani/critical

As cmd-amsterdam.nl is a Wordpress website it is advised to make use of a plugin which does the same thing. The plugin that is needed is autoptimize which is a great optimization plugin that also allows for loading in critical css. But before loading your critical css into autoptimiza you need to convert your css into critical css. A good tool for this is: https://jonassebastianohlsson.com/criticalpathcssgenerator/

For source and detailed information, check out:

https://www.wpfaster.org/blog/how-to-use-autoptimize-inline-and-defer-css-option

https://www.voorhoede.nl/en/blog/why-our-website-is-faster-than-yours/

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
