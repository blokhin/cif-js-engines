In-browser plugin-free CIF visualization: comparison of open-source engines
======

This utility web-app bundles four available open-source pure-JavaScript engines for in-browser rendering of [crystallographic information files (CIF)](https://en.wikipedia.org/wiki/Crystallographic_Information_File), for demonstration purposes:

* [JSmol, part of Jmol](http://www.jmol.org) (LGPL license)
* [ChemDoodle Web Components library](http://web.chemdoodle.com) (GNU General Public License version 3)
* [RasmolJS](https://bitbucket.org/baoilleach/rasmoljs) (derived from [RasMol](http://www.rasmol.org), licensed under GNU General Public License)
* [Player.html](https://github.com/tilde-lab/player.html) (MIT license)

Some web-server is required to run the web-app (however no server-side rendering is assumed), e.g. in Python:
```
python -m SimpleHTTPServer
```
