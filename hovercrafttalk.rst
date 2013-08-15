:title: Hovercraft - an alternative slide deck
:author: Kris Findlay
:description: Introduction to hovercraft slide deck
:keywords: presentation, restructuredtext, impress.js, python
:css: hovercrafttalk.css

This is the restructuredtext document

You can render this presentation to HTML with the command::

    hovercraft hovercrafttalk.rst slides

And then view the slides/index.html file to see how it turned out.

You can render this presentation to HTML with Presenter console command ::

    hovercraft -a hovercrafttalk.rst presenterslides

And then view the presenterslides/index.html file to see how it turned out.

Start of presentation.

----

:data-x: 0
:data-y: 10000

Hovercraft
==========

An Alternative Slide Deck
-------------------------

by Kris Findlay
...............

.. note::
    title slide

----

Who Am I ?
==========

* Kris Findlay
* Involved in the IT Support Industry
* Krisilis_ IT Support
* Using Linux For Over 10 Years

.. _Krisilis: http://www.krisilis.com

.. note::
    Dont Talk about you too much

----

Currently
=========

----

Archbang
========
.. image:: img/archlogo.png
    :width: 400px

.. note::
    an awesome distro .. bugger to update

----

LinuxMint
=========
.. image:: img/mintlogo.png
    :width: 400px

.. note::
    a great distro for new users
    includes all the main codecs etc..

----

What This is All About ?
========================

#. GUI Tools like Impress are lacking
#. Prezi Style slides look cool
#. We want something easy to use
#. Something we can edit easily
#. Automatic list no
#. Cool effects

.. note::

    Can use any text editor
    hovercraft is written in python
    convert restructured text in html slides
    using impress.js

----

We Can Load Images
==================

.. image:: img/ab_desktop.png
    :width: 400px
    :height: 300px

----

Move Horizontal
===============

----

:data-y: r500

Move Vertical
=============

----

:data-x: r1200
:data-rotate: 90

Rotate
======

----

:data-x: r4000
:data-scale: 5

Zoom
====

----

:data-scale: 0
:data-rotate-x: -180
:data-z: r0

As Well as 3D
=============

.. note::

    this slide seems to have disapeared off the screen.

----

:data-x: r1500
:data-rotate-z: 90

In
==

----

:data-y: r1000
:data-rotate-x: 90

Many
====

----

:data-y: r1000
:data-rotate-y: 90

Directions
==========

----

:data-y: r2500

Restructured Text
=================
is used to create the slides

::

    ---- denotes a new slide

.. note::
    Restructured text is a markup language heavily used in the python 
    sphinx documentation.
    doc utils is used to proccess the restructuredText

-----

:data-y: r3500

Titles
======
are created with *underlineing* the text

::

    title
    ===== denotesg H1
    title
    ----- denotes H2
    title
    ..... denotes H3

.. note::
    titles levels cannot be skipped

----

:data-y: r4500

Images
======
images are easy to include

::

    .. image: img/logo.png
        :width: 50px
        :height: 50px

.. note::
    any images included in slides will be copied to output folder

----

:data-x: r3000
:data-y: r3500

Preformated Text
================
can be included by using a

::

    ::
         indenting the text

----

:data-x: r3000
:data-y: r4500

Notes
=====
can be added to the rst file  by

::

    .. note::
            inented text as note

.. note::
    add more notes

----

:data-x: r3000
:data-y: r3500

Syntax Highlighting
===================

.. code:: python

    def day_of_year(month, day):
        return (month -1) * 30 + day_of_month

.. note::
    code is highlighted using pygments supporting various laguages
    code cal also be run using manuel

----

:data-y: r3000
:data-x: r4500

Position Fields
===============

fields starting with ``data-`` will be converted to impress.js attributes
eg ..

::

    data-x          x-axis
    data-y          y-axis
    data-z          z-axis
    data-rotate     rotation in degrees
    also data-rotate-x,y,z
    data-scale

.. note::
    positioning is abasalute by default. Relative is available by prepending
    value with "r" eg. r200px

----

:data-y: r3000
:data-x: r4500

Requirements
============

::

    Pygments==1.6
    configparser==3.3.0r2
    docutils==0.10
    hovercraft==1.2.dev0
    lxml==3.1.0
    svg.path==1.0b1
    wsgiref==0.1.2

hovecraft can be installed with command

::

    pip install hovercraft

----

:data-y: r3000
:data-x: r4444

Contact Me
==========

::

    Email : kris.findlay@krisilis.com
    twitter: azmodie
    Google Plus

*Any Questions ?*

hovercraft_ : https://github.com/regebro/hovercraft
restructuredText_ : http://docutils.sourceforge.net/rst.html
impressjs_ : https://github.com/bartaz/impress.js

.. _hovercraft: https://github.com/regebro/hovercraft
.. _restructuredText: http://docutils.sourceforge.net/rst.html
.. _impressjs: https://github.com/bartaz/impress.js

