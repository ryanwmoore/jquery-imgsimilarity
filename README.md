jQuery imgsimilarity
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
Project page: http://ryanwmoore.github.com/jquery-imgsimilarity/

Repository page: http://github.com/ryanwmoore/jquery-imgsimilarity/

Bug tracker: http://github.com/ryanwmoore/jquery-imgsimilarity/issues

Please use the bug tracker to report any issues/bugs/problems.

Demo
----
There is a demo.html file included. Please consult that for an example of using
the library. The images used in the demo are taken from http://pdphoto.org and
are in the public domain.

License
-------

This project is released under the Simplified BSD License:

Copyright (c) 2012, Ryan W. Moore
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met: 

1. Redistributions of source code must retain the above copyright notice, this
list of conditions and the following disclaimer. 

2. Redistributions in binary form must reproduce the above copyright notice,
this list of conditions and the following disclaimer in the documentation
and/or other materials provided with the distribution. 

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

The views and conclusions contained in the software and documentation are those
of the authors and should not be interpreted as representing official policies,
either expressed or implied, of Ryan W. Moore.
