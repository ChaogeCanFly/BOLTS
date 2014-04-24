---
  layout: post
  title: BOLTS release 0.3
  date: 2014-04-24 22:00:00
---

I am happy to announce a new release for [BOLTS]({{site.baseurl}}/index.html),
the Open Library of Technical Specifications. The distributions for
[OpenSCAD](http://www.openscad.org/), [FreeCAD](http://freecadweb.org/) and as
a collection of IGES files can be found on the [Download
page]({{site.baseurl}}/downloads.html).

There have been a lot of changes. git tells me, that (excluding changes in
generated files and drawings) 171 files changed, 16313 insertions and 1085
deletions happened. This still seems a bit high to me, probably due to binary
files and copies.

I tried to assemble a list of changes from the last release, and this is what I
came up with. It turns out I even managed to blog about most of it.

* [Python 2.6 compatibility]({{site.baseurl}}/2013/11/11/Python-2.6.html) for the FreeCAD backend
* [Common Parameters]({{site.baseurl}}/2013/11/29/BLT-file-progress.html)
* More and better automatic checks
* Many small and bigger improvements to the [webpage]({{site.baseurl}}/index.html)
* Improved structure of code, resulting in smaller distribution files
* Improvements for the [utility script]({{site.baseurl}}/doc/general/utility-script.html)
* [Connectors for OpenSCAD]({{site.baseurl}}/2013/12/27/OpenSCAD-positioning.html)
* [An IGES backend and distribution]({{site.baseurl}}/2014/01/07/IGES-backend.html)
* [PySide compatibility]({{site.baseurl}}/2014/01/13/PySide-and-Tables.html) for newer versions of FreeCAD
* [2D tables]({{site.baseurl}}/2014/01/13/PySide-and-Tables.html)
* [Colored threaded faces]({{site.baseurl}}/2014/02/02/News-Digest.html) in FreeCAD and OpenSCAD
* More parts, the automatic counter claims 56 classes in 12 collection covering more than 2200 different parts (but this number is a bit inflated)

What makes me very happy, is that people started to contribute parts, the
automatic counter lists 6 individuals that contributed parts data or
geometries. I also received quite a bit of positive feedback, which is really
encouraging. I think BOLTS is a good idea that deserves to be explored, and I
am glad that I am not the only one to think so.

There remains [a lot to be
done](https://github.com/jreinhardt/BOLTS/issues?state=open). I have many
ideas, and there are plenty of issues, where the current structure and
architecture of BOLTS is not adequate. After attacking the structural issues
that I am aware of right now, I want to add more parts for the next release,
making BOLTS more useful and uncovering problems that have not yet been found.
This is something that you can help with, and I encourage you and try to
support you with that as good as I can.