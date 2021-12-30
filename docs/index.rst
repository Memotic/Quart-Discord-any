.. Quart-Discord documentation master file, created by
   sphinx-quickstart on Wed May  8 08:29:45 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Quart-Discord-any's documentation!
=========================================

.. image:: /images/background.jpg

Quart-Discord is an extension made for Quart which makes implementation of
Discord's OAuth2 API easier.

**Features**

- Asynchronous wrapper.
- Clean object-oriented design.
- Covers most of the scopes provided by the API.
- Supports various discord models and objects.
- An internal smart caching layer to increase the performance.

**Differences to the original Quart-Discord**

As of right now `Quart-Discord <https://github.com/jnawk/Quart-Discord>`_ requires discord.py which is no longer maintained, but has two popular forks: py-cord and nextcord.

Other forks of Quart-Discord support py-cord and nextcord, respectively, but are different packages.

This fork aims to add support for all three Discord libraries by using the "extras" functionality

Contents
--------

.. toctree::
   :maxdepth: 3

   introduction
   api



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
