================================
collective.ptg.bootstrapcarousel
================================

Introduction
============

Basic integration of the `Twitter Bootstrap Carousel`_ with 
`collective.plonetruegallery`_

This add-on will only work with Plone >= 4.3 as `jQuery`_ 1.7 
is not supported on previous versions of Plone.

**Bootstrap's Carousel** needs `jQuery`_ 1.7 or higher.


Requirements
============

- From the Plone 4.3.x latest version (https://plone.org/download)
- The `collective.plonetruegallery`_ package (*will be installed as 
  a dependency of this package*)


How It Works
============

You can enabled the ``Bootstrap Carousel`` gallery display type follow the steps:

- at the top right corner of the page click on the ``Admin`` drop down menu 
- choose ``Site Setup``
- at the ``Add-on Configuration`` 
- click on ``Plone True Gallery settings`` section
- at the ``Main`` tab changes the ``Gallery Display Type`` option with 
  the ``Bootstrap Carousel`` value

The ``collective.ptg.bootstrapcarousel`` package include the gallery display type 
called ``Bootstrap Carousel`` and this have a configlet like the following:

.. image:: https://github.com/collective/collective.ptg.bootstrapcarousel/raw/master/docs/ptg_bootstrapcarousel_controlpanel.png

Them, you can see how looks like the ``Bootstrap Carousel`` gallery display type 
from a Folder as the following:

.. image:: https://github.com/collective/collective.ptg.bootstrapcarousel/raw/master/docs/ptg_bootstrapcarousel_view.png


Features
========

- It's an installable Plone package.
- After installation from ``Add-ons`` controlpanel, you can changes the 
  ``PloneTruegallery settings`` globally or locally.
- It's have support for clean uninstallation.


Installation
============


If you are a developer, you might enjoy installing it via buildout.

For install ``collective.ptg.bootstrapcarousel`` package add it to 
your ``buildout`` section's *eggs* parameter e.g.:

::

   [buildout]
    ...
    eggs =
        ...
        collective.ptg.bootstrapcarousel


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file:

::

    install_requires=[
        ...
        'collective.ptg.bootstrapcarousel',
    ],


Contribute
==========

- Issue Tracker: https://github.com/collective/collective.ptg.bootstrapcarousel/issues
- Source Code: https://github.com/collective/collective.ptg.bootstrapcarousel


License
=======

The project is licensed under the GPLv2.


Credits
-------

- Jason Murphy (json.murphy at gmail dot com).


Amazing contributions
---------------------

- Leonardo J. Caballero G. aka macagua (leonardocaballero at gmail dot com).

You can find an updated list of package contributors on https://github.com/collective/collective.ptg.bootstrapcarousel/contributors

.. _`Twitter Bootstrap Carousel`: http://twitter.github.io/bootstrap/javascript.html#carousel
.. _`collective.plonetruegallery`: https://pypi.org/project/collective.plonetruegallery/3.3.2/
.. _`jQuery`: https://jquery.com/
