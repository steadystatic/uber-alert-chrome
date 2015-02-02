# uber-alert-chrome
Quick bookmarklet turned into Chrome extension for m.uber.com

![Chrome Uber Alert](https://raw.githubusercontent.com/steadystatic/uber-alert-chrome/master/screenshot-example.png)

## Why

Sometimes you're busy working (or not) and can't hit Request Uber a
bunch when volume is high. This Chrome extension helps by making some
noise on your m.uber.com tab so you can spring into action when an Uber
is available.

## How to use

- Download [uberalert.crx](https://github.com/steadystatic/uber-alert-chrome/raw/master/uberalert.crx)
- Open [chrome://extensions](chrome://extensions) in Chrome, and drag in uberalert.crx. Allow it
- Open a tab to [m.uber.com](http://m.uber.com). Click Uber Alert icon

Make sure your volume is turned up and listen for a car honk :)

## Make your own changes

To make changes just edit bookmarklet.js and to build a new .crx file you'll need the package crxmake and signing it with a PEM file like this:

crxmake --pack-extension=~/Downloads/uber-alert-chrome/uber-alert-chrome-ext  --extension-output=~/Downloads/uber-alert-chrome/uberalert.crx
