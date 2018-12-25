# Mapbox Controls
* Localization
* Ruler
* Styles
* Zoom
* Compass

`npm i mapbox-gl-controls`



[Examples](https://bravecow.github.io/mapbox-gl-controls/)


~~~~

## changes by tin6150, these are study notes, no intention to upload back to original source 



`npm install mapbox-gl-controls`

[Examples tin6150](https://tin6150.github.io/mapbox-gl-controls/)

More specific examples??  Maybe in increasing order of complexity?

These js doesn't generate working web page :(
the fact that they used a bundler with a webpack.config.js means i have to learn to decode that to see what it is doing... 

* https://tin6150.github.io/mapbox-gl-controls/examples/styles.js
* https://tin6150.github.io/mapbox-gl-controls/examples/zoom-compass.js
* https://tin6150.github.io/mapbox-gl-controls/examples/localization.js
* https://tin6150.github.io/mapbox-gl-controls/examples/ruler.js - need turf js to do the calculation of the measurements.  definately quite involved.  npm add a @turf, also install mapbox-gl module, etc.


https://tin6150.github.io/mapbox-gl-controls/
is build by github pages (Jekyl) using master branch, doc/ folder

will try to edit some of those files to see how the plugin is really made to work.

seems to be client side js.  since page is served by github.io
package install was likely by npm
they used webpack 
to create a bundle
which may have put all the js code in single place
may have circumvented some of the problems i had with CORS or https access, etc.

wonder if mapbox had created public accessible url for their js, like their tile api pages, would have make using these feature easier.


