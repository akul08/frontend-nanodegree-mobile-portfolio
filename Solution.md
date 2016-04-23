# Got 90 above score on pagespeed insights

## Page Speed Insights
* `https://developers.google.com/speed/pagespeed/insights/`

# Image Optimization:
* Compress images from `https://kraken.io/web-interface`

# CSS BLock Rendering:
* inline css
* make async by using    
 ` <link href=css/style.css rel=stylesheet media="none" onload="if(media!='all')media='all'">
   <noscript>
        <link href=css/style.css rel=stylesheet>
    </noscript>
`
* Add media to css
    `<link href=css/print.css rel=stylesheet media="print">`

# Fonts Block Rendering
* `    <link href=//fonts.googleapis.com/css?family=Open+Sans:400,700 rel=stylesheet media="none" onload="if(media!='all')media='all'">
`
 `   <noscript>
        <link href=//fonts.googleapis.com/css?family=Open+Sans:400,700 rel=stylesheet>
    </noscript>
`

# JS Block Rendering:
* Make js async.

# Minify HTML, CSS, JS

# Cache using meta tag
* `<meta http-equiv="cache-control" content="max-age=0" />`
* `<meta http-equiv="cache-control" content="no-cache" />`
* `<meta http-equiv="expires" content="0" />`
* `<meta http-equiv="expires" content="Tue, 01 Jan 1980 1:00:00 GMT"  />`
* `<meta http-equiv="pragma" content="no-cache" />`

# Cache using .htaccess