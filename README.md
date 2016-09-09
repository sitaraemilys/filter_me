
## Introduction
This is a little filter app which enables one to drag and drop an image, which is then resized to fit into a 500x500 square and can then have funky filters applied to. Oooerr.

<img src="public/assets/img/screenshot.png"/>

## Instructions
Click [here] (https://sity-filter-me.herokuapp.com/) to explore it online.

To install and use locally:
```
$ git clone git@github.com:sitypop/filter_me.git
$ cd filter_me
$ node bin/http-server
```
Then open your browser, visit `http://localhost:8080`.

## Tools used
* JQuery
* FileReader.js: This is a lightweight wrapper around the HTML5 drag/drop events that makes them much easier to work with. It also adds a method to jQuery, so you can bind the events to a specific element.
* JQuery MouseWheel: Plugin to scroll the filter container.
* Caman.js: This is a canvas manipulation library that allows you to apply various effects and filters on an image.
