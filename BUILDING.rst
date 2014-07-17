Building a Local Copy
=====================

If you are interested in building a local copy of the Ngx CC documentation, you
can follow these instructions to do so. We ask that you *do not* publish this on
the internet. Doing so could cause issues with search engines and we'd really
just prefer avoid that headache.

Local builds are best suited for learning documentation syntax as well as
testing changes to modules.

Requirements
------------

In order to build this documentation locally, you will need:

* A copy of this repository
* Python
* Sphinx
* Pygments
* BeatuifulSoup4

If you're using Debian, this can be done with the following command:

    aptitude install python python-sphinx python-pygments python-bs4

Building Docs
-------------

Building the docs is rather simple. We'll assume you pulled the entire
repository to ``/home/bob/docs/``.

To build the full documentation:

    sphinx-build /home/bob/docs/source /home/bob/docs/output

If all went well, you will now now be able to browse these from your web
browser. The link will be similar to:

    file:///home/bob/docs/output/index.html

Missing Theme
-------------

The theme these docs use is provided by Read the Docs. Including it in your
local build adds a fair amount of extra work and isn't needed during testing.
How to include it has been intentionally omitted.
