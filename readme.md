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
*   Make use of an ssl certificate and only use https
*   Make as few http requests as possible -> bundle small files & assets together.

### HTTP/1

*   Add some more points here...

### HTTP/2

*   Add some more points here...
*   Supports compression of request headers and uses binary protocol (among more improvements) -> results in better load times
*   Make sure to use https in your website
*   Make sure that your hosting provider supports http2

## Caching

*   Caching static assets on the website are very helpful to improving the overall usability of your website. For example by caching images the website does not have to load the images everytime you revisit the website. This can hugely improve the load speed of your website. Furthermore having caching can alsio ensure better user experience when the user loses internet connection. By caching visited pages the user is still able to continue navigating the website and viewing / reading its content. 
* One way of doing this would be to add a service worker. 
* For Wordpress werbsites there are several good caching plugins that can be installed. 

## Minification

*   Minifying the Javascript and CSS files can improve load times and performance of the website. When executing a file there is no need for most of the white space that make javascript or css files more readable. Therefore it is wise to minify these pages.
* One way of doing this is running Uglify with npm 
* There are also a lot of free online tools to do thi such as https://cssminifier.com/. Simply input your css and a minified versiobn is returned.

### Images

*   When serving static images it is very important that they are optimized and correctly size. Large image files can dramatically slow down a websites' load time. 
* Firstly it is wise to allways resize your images to an apropriate size. Then you can use an online tool to compress the image and strip it of unwanted data. A tool for this is http://optimizilla.com/ . 
* With Wordpress it is always recommended to use an image optimization plugin to automatically resize and compress your image files. 

### CSS

*   Minify your CSS through online tools or handy npm modules
*   The less css the better. Don't write redundant css. Be smart about writing and organizing your css

### HTML

*   Use text compression like Gzip

### JavaScript

*   Minify your JS. Can be done with Uglify-JS or online tools

### Fonts

*   Only load the webfonts and the font-styles you need. 
*   For best performance use fonts that have standard OS UI support

## Perceived Performance

*   Perceived performance is very important for websites. The faster a page loads the more likely a user will stay on a website. Every second counts when loading your websites content. One way of improving perceived performance is to reduce render blocking css and scripts. These scripts and stylesheets first have to be loaded before content on a page can be properly loaded. By making these scripts and stylesheets load asynchronously, and adding the most 'critical' css and js directly to the pages content, a user can quickly see the 'first paint' of the website so that the rest of the websites content can be loaded outside of the viewport. This also also called 'above the fold content' 

## Performance

*   Add some more points here...

### Images

*   Add some more points here...
* Use WebP format
* Correctly size images. Possibly use different sizes for different viewports
* Strip images from unnecessary data
* Compress images
* Use inline svg where possible


### CSS

*   Add some more points here...
* Minify css
* Remove unused css
* load stylesheets async and use critical css
* Be wise with writing your css. Don't write duplicate code -> strive for less css and keep it organized

### HTML

*   Add some more points here...
*   Compress your text files -> Gzip
*   Use server side rendering to load in content

### JavaScript

*   Add some more points here...
* Minify JS. Gulp or Uglify-JS are good ways of doing this
* Make sure scripts are not render blocking
* 

### Fonts

*   loading in external fonts can cause the page to load slower due to the fonts having to be loaded in. FIrstly it is always wise to have a fallback font in case the external font is not properly loaded or unavailable. Secondly, it is wise to load your websonts asynchronously. This will improve the load time of your website. Thirdly, if you really want your website to load your font fast, it might be a good idea to not opt for webfotns but to choose standard OS supported fonts. One example of a good combination of system ui fonts and fallbacks:

`
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
}
`

## Backend optimisation

*   Use browserify for bundeling your Javascript and the minifying it alltogether
*   Use server side content rendering
* 
