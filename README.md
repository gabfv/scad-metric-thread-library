# A library for creating metric bolts and nuts in OpenSCAD
This is a remix of a remix from Thingiverse. It allows you to create metric bolts and nuts, along with other useful elements that I've modified.

This library started from the work of Trevor Moseley (_TrevM_) :
[OpenSCAD ISO metric thread library / functions (updated)](http://www.thingiverse.com/thing:311031)

It was then tweaked by _JustKrys_ to work with Cura and to match actual steel nuts and bolts :
[Remix of Trevor Moseley's "OpenSCAD ISO metric thread library / functions (updated)", tweaked to work on Ultimaker 2 with Cura.](https://www.youmagine.com/designs/openscad-metric-nut-bolt-threads-library)

This is intended to work with **OpenSCAD 2015.03** and **Cura** (tested with 2.3.1).

Here's a list of features that I've added so far :
- An easy way to make a cube with a threaded hole at its center. I found it easier to merge a block instead of trying to merge a threaded cylinder (the cylinder isn't also a perfect circle) with an existing mesh in MeshMixer and/or 123Design.
- Make some insert bolt. It basically let you have bolts that screw inside each other. =)
