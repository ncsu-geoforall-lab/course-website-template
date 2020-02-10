NCSU GeoForAll Course Website Template
======================================

To see template extending with additional functionality see:

https://github.com/ncsu-geoforall-lab/geospatial-modeling-course

For different approach see:

https://github.com/ncsu-geoforall-lab/grass-temporal-workshop

To learn about Git and GitHub, you can use:

http://ncsu-geoforall-lab.github.io/git-and-github-workshop/

Requirements
------------

Pandoc when using `.rst` files.

How to use it
-------------

To build the pages, run ``./build.sh``. 
This will create directory ``build`` on the repository root level.
To preview the resulting website, open ``build/index.html``.

The pages are published online through GitHub Pages (``gh-pages``
branch). The build and publishing happens automatically using GitHub
Actions (defined in ``.github/workflows/`` directory). To do the same
in your new repository, you need to
`set up Deploy key and a Secret <https://github.com/marketplace/actions/github-pages-action#1-add-ssh-deploy-key>`_
for your repository.

Authors
-------

Copyright 2013-2020 by

* Vaclav Petras, NCSU GeoForAll Lab
* Anna Petrasova, NCSU GeoForAll Lab


License and use
---------------

The template is this repository are under CC BY-SA 4.0 license.

https://creativecommons.org/licenses/by-sa/4.0/

If you are not connected with NCSU GeoForAll, please, consider changing
the colors in some way, so you don't have completely same color schema
as NCSU GeoForAll websites. Although this is totally optional, it
would be highly appreciated.
