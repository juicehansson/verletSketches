Working with Verlet-js
=========

This project is meant to give a couple of examples on how Verlet.js is a powerfull library to create interesting and creativ interaction. Verlet can be used in many ways but we chose to look at it as a tool for making flat 2d into something interesting and playfull. In combination with audio library and device orientation simple shapes can become something you physically engage with. 



License for Verlet
-------
You may use verlet-js under the terms of the MIT License (See [LICENSE](LICENSE)).


Sketches
--------

1. [Josefine](http://subprotocol.com/verlet-js/examples/shapes.html)
2. [Alison](http://subprotocol.com/verlet-js/examples/tree.html)
3. [Anna](http://subprotocol.com/verlet-js/examples/cloth.html)


Other sources and helping tutorials
--------
1. [Building shapes tutorial](https://www.sitepoint.com/an-introduction-to-verlet-js/)
2. [Device orientation](https://developers.google.com/web/fundamentals/native-hardware/device-orientation/)
3. [Web audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
4. [Volume meter](https://github.com/cwilso/volume-meter/)


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

