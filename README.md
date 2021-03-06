# Augmented Reality
This folder has code for A-Frame augmented reality projects. 
A-Frame can be used to develop AR projects, but at the moment only seems to work with Andriod phones and not on all browsers. It should work in Chrome and Samsung mobile browser.

## Resources
These project use the following Libraries, API's and software

- The QR code code uses the [Bar Code Detection API](https://developer.mozilla.org/en-US/docs/Web/API/Barcode_Detection_API). This works on some mobile browsers and on a Mac on the chrome browser. It doesn't work on web browsers if you are using a Windows OS.
- A-Frame
- Blender
- Gimp

## index.html
This will be different content depending on what I'm working on.

## dinosaure.html
This file was developed from a [project I found on line](https://aframe.io/blog/webxr-ar-module/), you can see their [code on glitch](https://glitch.com/edit/#!/xr-spinosaurus?path=style.css%3A1%3A0). I made changes so the dinasaur will always appear close to where the person is pointing the camera. In VR mode, if you press the pink box the dinasuar will toggle to appear or disappear. If the camera postion has moved the dinasaur will appear near the new camera position when toggled back on.

## qr.html
This file was developed from an [online project](https://itnext.io/creating-a-real-time-qr-code-scanner-with-vanilla-javascript-part-1-2-creating-the-scanner-a8934ee8f614) it starts a video and reads a qr code

## ar.html
This file was developed from a [project I found on line](https://aframe.io/blog/webxr-ar-module/), you can see their [code on glitch](https://glitch.com/edit/#!/xr-spinosaurus?path=style.css%3A1%3A0). It is simplifying the code.

## video.html
This file can read a qr code and also uses A-Frame to show 3D objects through the camera into the real scene (AR). It is based on [this code](https://glitch.com/edit/#!/stack-57493298) from this [stackoverflow question](https://stackoverflow.com/questions/57493298/a-frame-with-device-camera-how-to-see-video-behind-the-a-scene) and from this qr code tutorial from this [online tutorial](https://itnext.io/creating-a-real-time-qr-code-scanner-with-vanilla-javascript-part-1-2-creating-the-scanner-a8934ee8f614)

A 3D rectanble will appear in the aqua sphere when a QR code with the data https://example.com/ is registered by the camera.


## aframemodels.html
This file is to try out 3D models in VR and work out the translations and animations

## tunnel.html
This file has the tunnel model for AR. I'm playing around with the transparency of the 3D model and found these resources useful for getting the transparency from a blender model to work in A-Frame [transparency in A-Frame](https://stackoverflow.com/questions/62236739/a-frame-ignoring-3d-models-slightly-transparent-materials) and [glitch of it working](https://aframe-transparent-material.glitch.me/)

## rain.html rain2.html rain3.html
This file uses A-Frame particle systemm to make rain and loads in png images to create an effect of rain hitting water. The png loader comes from [this stackoverflow question](https://stackoverflow.com/questions/58113667/animating-a-series-of-png-images-in-a-frame-ar-js) and the [fiddle for the answer](https://jsfiddle.net/Lwtzjnk9/1/)

Each file has slightly different funcitonality. Rain doesn't have the AR added, rain2 does and has the code for click interactions, rain3 doesn't have the click interactions
## tests
This file contains code I've used for testing and other code that might no longer be in one of the html files.

## webxr1Basic.html webxr2Animation.html webxr3TouchEvent.html, webxr4HitTest.html
These files are my workings from the Udemy course Intro to Augmented Reality on the Web: WebXR and Three.js

webxr1Basic.html is the basics of getting AR to work on iOS and Android using WebXR api. 
Webxr2Animation.html is getting objects into the scene, and simple animations.
webxr3TouchEvent.html is adding touch events. On single click a mesh appears on the screen, on a double click all the added meshes are removed
webxr4HitTest.html adds the code to check for surfaces using a hit test, adds an object ot show the surface has been found, then you can click to add an object to that point. Double clicking removes all the meshes

## sandbox.html
Tests with AR and QR codes and AI