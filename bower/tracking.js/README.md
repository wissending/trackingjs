# tracking.js

[![Build Status](http://img.shields.io/travis/eduardolundgren/tracking.js.svg?style=flat)](https://travis-ci.org/eduardolundgren/tracking.js)
[![DevDependencies Status](http://img.shields.io/david/dev/eduardolundgren/tracking.js.svg?style=flat)](https://david-dm.org/eduardolundgren/tracking.js#info=devDependencies)

The *tracking.js* library brings different computer vision algorithms and techniques into the browser environment. By using modern HTML5 specifications, we enable you to do real-time color tracking, face detection and much more with a simple and intuitive interface.

* [Official website](http://trackingjs.com)
* [Documentation](http://trackingjs.com/docs.html)
* [API Docs](http://trackingjs.com/api/)

## Install

Install via [Bower](http://bower.io/) or [download as a zip](https://github.com/eduardolundgren/tracking.js/archive/master.zip):

```
bower install tracking.js
```

## Examples

[![Demo 1](https://cloud.githubusercontent.com/assets/398893/3691378/d90f0d60-1351-11e4-9872-2d5abcef43ad.jpg)](#)
[![Demo 2](https://cloud.githubusercontent.com/assets/398893/3691387/eca4cf22-1351-11e4-94d3-905740bd09dc.jpg)](#)
[![Demo 3](https://cloud.githubusercontent.com/assets/398893/3691391/f86b0024-1351-11e4-82bf-3c44a4768d70.jpg)](#)

## Features

* [Trackers](http://trackingjs.com/docs.html#trackers)
  * [Color Tracker](http://trackingjs.com/docs.html#color-tracker)
  * [Object Tracker](http://trackingjs.com/docs.html#object-tracker)
* [Utilities](http://trackingjs.com/docs.html#utilities)
  * [Feature Detection (Fast)](http://trackingjs.com/docs.html#feature-detection)
  * [Feature Descriptor (Brief)](http://trackingjs.com/docs.html#feature-descriptor)
  * [Convolution](http://trackingjs.com/docs.html#convolution)
  * [Gray Scale](http://trackingjs.com/docs.html#gray-scale)
  * [Image Blur](http://trackingjs.com/docs.html#image-blur)
  * [Integral Image](http://trackingjs.com/docs.html#integral-image)
  * [Sobel](http://trackingjs.com/docs.html#sobel)
  * [Viola Jones](http://trackingjs.com/docs.html#viola-jones)
* [Web Components](http://trackingjs.com/docs.html#web-components)
  * [Color Element](http://trackingjs.com/docs.html#color-element)
  * [Object Element](http://trackingjs.com/docs.html#object-element)

## Browser Support

You can plug *tracking.js* into some well suported HTML elements such as `<canvas>`, `<video>` and `<img>`.

![IE](https://cloud.githubusercontent.com/assets/398893/3528325/20373e76-078e-11e4-8e3a-1cb86cf506f0.png) | ![Chrome](https://cloud.githubusercontent.com/assets/398893/3528328/23bc7bc4-078e-11e4-8752-ba2809bf5cce.png) | ![Firefox](https://cloud.githubusercontent.com/assets/398893/3528329/26283ab0-078e-11e4-84d4-db2cf1009953.png) | ![Opera](https://cloud.githubusercontent.com/assets/398893/3528330/27ec9fa8-078e-11e4-95cb-709fd11dac16.png) | ![Safari](https://cloud.githubusercontent.com/assets/398893/3528331/29df8618-078e-11e4-8e3e-ed8ac738693f.png)
--- | --- | --- | --- | --- |
IE 9+ ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ |

However, the browser support may vary if you request the user's camera (which relies on [getUserMedia API](http://caniuse.com/#feat=stream)).

## Roadmap

- [ ] Optical flow
- [ ] Face recognition
- [ ] Pose estimation
- [ ] Faster keypoint descriptor (BRIEF)
- [ ] More trainings (Hand, car plate, etc)

## Team

*tracking.js* is maintained by these people and a bunch of awesome [contributors](https://github.com/eduardolundgren/tracking.js/graphs/contributors).

[![Eduardo Lundgren](https://2.gravatar.com/avatar/42327de520e674a6d1686845b30778d0)](https://github.com/eduardolundgren) | [![Thiago Rocha](https://2.gravatar.com/avatar/09c627c62a26a770200819a41a71a3eb)](https://github.com/thiago-rocha) | [![Zeno Rocha](https://2.gravatar.com/avatar/e190023b66e2b8aa73a842b106920c93)](https://github.com/zenorocha) | [![Pablo Carvalho](https://2.gravatar.com/avatar/ae10d2692a6adbf051c6d4255e222df8)](https://github.com/mairatma) | [![Maira Bello](https://2.gravatar.com/avatar/97e0e62c9c02badba4c321f7613e6acf)](https://github.com/mairatma)
--- | --- | --- | --- | ---
[Eduardo Lundgren](https://github.com/eduardolundgren) | [Thiago Rocha](https://github.com/thiago-rocha) | [Zeno Rocha](https://github.com/zenorocha) | [Pablo Carvalho](https://github.com/pablocp) | [Maira Bello](https://github.com/mairatma)

## License

[BSD License](https://github.com/eduardolundgren/tracking.js/blob/master/LICENSE.md) © Eduardo Lundgren