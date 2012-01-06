==========
Colorcount
==========

A quick-and-dirty script that I use to analyze use of color in CSS-files.

Usage
=====

Create a neat HTML-document containing a list of all colors found::

    colorcount static/style/master.css > test.html && \
        open -a Firefox test.html
