# Augmented Reality
This folder has code for A-Frame augmented reality projects. 
A-Frame can be used to develop AR projects, but at the moment only seems to work with Andriod phones and not on all browsers. It should work in Chrome and Samsung mobile browser.

The QR code code uses the [Bar Code Detection API](https://developer.mozilla.org/en-US/docs/Web/API/Barcode_Detection_API). This works on some mobile browsers and on a Mac on the chrome browser. It doesn't work on web browsers if you are using a Windows OS.

## index.html
This project was developed from a [project I found on line](https://aframe.io/blog/webxr-ar-module/), you can see their [code on glitch](https://glitch.com/edit/#!/xr-spinosaurus?path=style.css%3A1%3A0)

## dinosaure.html
This file was developed from a [project I found on line](https://aframe.io/blog/webxr-ar-module/), you can see their [code on glitch](https://glitch.com/edit/#!/xr-spinosaurus?path=style.css%3A1%3A0). I made changes so the dinasaur will always appear close to where the person is pointing the camera. In VR mode, if you press the pink box the dinasuar will toggle to appear or disappear. If the camera postion has moved the dinasaur will appear near the new camera position when toggled back on.

## qr.html
This file was developed from an [online project](https://itnext.io/creating-a-real-time-qr-code-scanner-with-vanilla-javascript-part-1-2-creating-the-scanner-a8934ee8f614) it starts a video and reads a qr code

## ar.html
This file was developed from a [project I found on line](https://aframe.io/blog/webxr-ar-module/), you can see their [code on glitch](https://glitch.com/edit/#!/xr-spinosaurus?path=style.css%3A1%3A0). It is simplifying the code.

## video.html
This file can read a qr code and also uses A-Frame to show 3D objects through the camera into the real scene (AR). It is based on [this code](https://glitch.com/edit/#!/stack-57493298) from this [stackoverflow question](https://stackoverflow.com/questions/57493298/a-frame-with-device-camera-how-to-see-video-behind-the-a-scene) and from this qr code tutorial from this [online tutorial](https://itnext.io/creating-a-real-time-qr-code-scanner-with-vanilla-javascript-part-1-2-creating-the-scanner-a8934ee8f614)

## tests
This file contains code I've used for testing and other code that might no longer be in one of the html files.