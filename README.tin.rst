

on bofh
updated to use nodesource version of nodejs, so to get to version 10.x
os bundled version is way old?  0.10.... ???

npm install webpack

cd docs
../node_module/.bin/webpack

created some changes

	modified:   docs/build/bundle.css
	modified:   docs/build/bundle.js
	modified:   package-lock.json
	modified:   package.json

let's see if these check in get my version of index_styles.html to work...


*sigh* how deep does the rabbit holes go?
and this was supposed to be simple example for people to learn from??!!

modified docs.js
commented out js that i didn't care
webpack generated new bundle.js
but then it still look for exampleLocalization

how deeply nested/interdependent are these examples?

seeking help, let's see...
https://github.com/bravecow/mapbox-gl-controls/issues/3
