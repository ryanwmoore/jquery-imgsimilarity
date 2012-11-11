jQuery imgSimilarity
====================

About
-----
This jQuery library enables image similarity calculations. It uses a histogram
based approach to calculate how similar images are. It is rather simple and
examines only R, G, B values but, nevertheless, be careful when using it on
many images or large images (especially on mobile devices) -- as it may be
slow. The calculation is done once and requires little memory.

Usage
-----
See the demo.html file. Be sure that the image has completely loaded before you
try to compute its histogram! See the demo.html for an example of how to do
this.

Requirements
------------

jQuery: http://jquery.com/ -- tested with v1.8.2.

A browser that supports canvas. Tested in Firefox 16 and Internet Explorer 9.
It doesn't do anything very fancy with canvas and so should work in other
browsers.

Contact
-------
Project page is at: http://ryanwmoore.github.com/jquery-imgsimilarity/
Bug tracker: http://github.com/ryanwmoore/jquery-imgsimilarity/issues

Please use the bug tracker to report any issues/bugs/problems.
