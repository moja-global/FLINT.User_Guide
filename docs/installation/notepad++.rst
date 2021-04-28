.. Notepad++ Installation Guide

*******************************
1. Notepad++ Installation Guide
*******************************

.. _installing_notepad++:

.. toctree::
   :maxdepth: 2
   :caption: Contents:


.. image:: ../_static/npp/logo.png



1.1. Overview
=============

In this guide, we'll explore how to build the **FLINT Base Image** from source using Docker.

-----

1.1. Prerequisites
==================

Before we begin, we should fulfill all the requirements laid out in the :ref:`Introductory Guide <introductory_guide_prerequisites>`. 

-----

1.3. Steps
==========


**1.3.1. Downloading Notepad++**

+-----+------------------------------------------+------------------------------------------+
| 1.1 | .. image:: ../_static/npp/download_1.png | | Let's begin by searching for Notepad++ |
|     |                                          | | on our browser                         |
+-----+------------------------------------------+------------------------------------------+
| 1.2 | .. image:: ../_static/npp/download_2.png | | Next, let's click on the               |
|     |                                          | | notepad-plus-plus.org link             |
+-----+------------------------------------------+------------------------------------------+
| 1.3 | .. image:: ../_static/npp/download_3.png | | Select **Download**, on the left,      |
|     |                                          | | and click on the latest release of     |
|     |                                          | | Notepad++ on the right to download it  |
+-----+------------------------------------------+------------------------------------------+


**1.3.2. Installing Notepad++**

+-----+------------------------------------------+------------------------------------------+
| 1.1 | .. image:: ../_static/npp/download_1.png | Search for Notepad++ on your browser     |
+-----+------------------------------------------+------------------------------------------+
| 1.2 | .. image:: ../_static/npp/download_2.png | Click the Notepad++ link                 |
+-----+------------------------------------------+------------------------------------------+
| 1.3 | .. image:: ../_static/npp/download_3.png | | Select **Download**, on the left,      |
|     |                                          | | and click on the latest release of     |
|     |                                          | | Notepad++ on the right to download it  |
+-----+------------------------------------------+------------------------------------------+

Let's start by navigating to the `Notepad++ Downloads Page <https://notepad-plus-plus.org/downloads/>`_:

.. code-block::

   git clone https://github.com/moja-global/FLINT.Docker.git 

    
Next, let's change our working directory to the directory containing the Base Image's Dockerfile:

.. code-block::

   cd FLINT.Docker/docker/baseimage-bionic
    

Next, let's build our FLINT Base Image using the command below:

.. code-block::

   docker build  .

.. Caution:: The building of this image is time expensive and as such should be done when we have sufficient time to spare.   

