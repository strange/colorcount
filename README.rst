==========
Colorcount
==========

A quick-and-dirty script that I use to analyze use of color in CSS-files.

Usage
=====

You can supply input to analyze by specifying file(s) (space-delimited) or
through stdin. Output is written directly to stdout (currently hardwired to
output everything formatted as HTML).

Analyze a local file and redirect output to a file::

    colorcount static/style/master.css > out.html

Download a remote file and pipe output through the script::

    curl http://openbsd.org/ | colorcount
