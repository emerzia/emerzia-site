
Emerzia website
---------------

This folder contains the source used to generate a static site by nikola.

Installation and documentation at http://nikola.ralsina.com.ar

Configuration file for the site is `conf.py`.

To build the site::

    nikola build

To see it::

    nikola serve

And point your browser to http://localhost:8000


To check all available commands::

    nikola help

Copy & deploy::

    cp -rf output/* /home/areski/public_html/Emerzia/emerzia.github.io/
    cd /home/areski/public_html/Emerzia/emerzia.github.io
    git commit -a -m "website update : description"
    git push
