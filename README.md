Working with Verlet-js
=========

This project is meant to give a couple of examples on how Verlet.js is a powerful library to create interesting and creative interaction. Verlet can be used in many ways but we chose to look at it as a tool for making flat graphics into something interesting and playful. In combination with audio library and device orientation simple shapes can become something you physically engage with. 

[Verlet.js](https://github.com/subprotocol/verlet-js)


Our demo shows a setting where users can drag and pull on objects. The shapes are also reactive to device orientation. With the help of the functions of Verlet.js you can add behavior to objects which might be very helpful in prototyping. The device orientation is only working on computers who have those sensors.  

All you have to do is to download this code to try it out.
The files we have changed in this repository is css, demo, sketches, images, index and readme. The other files are from the original code linked above.

Sketches
--------

1. [Josefine](sketches/sketch-01/donkey.html)
2. [Alison](sketches/alisons_sketches/sketch2.html)
3. [Anna](sketches/sketchA.html)

Demo
--------

[Demo](demo/finalsketch.html)


Other sources and helping tutorials
--------
1. [Building shapes tutorial](https://www.sitepoint.com/an-introduction-to-verlet-js/)
2. [Device orientation](https://developers.google.com/web/fundamentals/native-hardware/device-orientation/)
3. [Web audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
4. [Volume meter](https://github.com/cwilso/volume-meter/)



Info Verlet.js
-----------

Code Layout 
-----------
1. js/verlet-js/vec2.js: _2d vector implementation_
2. js/verlet-js/constraint.js: _constraint code_
3. js/verlet-js/verlet.js: _verlet-js engine_
4. js/verlet-js/objects.js: _shapes and objects (triangles, circles, tires..)_

Build for npm
-------------

``` js
npm run build
```

License for using Verlet.js
-------
You may use verlet-js under the terms of the MIT License (See [LICENSE](LICENSE)).

