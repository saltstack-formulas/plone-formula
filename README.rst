=============
plone-formula
=============

This formula installs plone via buildout. The formula can be used either by forking or extending. When forking, the buildout.cfg in files/base can be adapted.
When buildout configuration is stored in i.e. a git repository, the plone formula can be extended and the buildout_basefiles state has to be overridden in the derived formula.


.. note::

Suggestions, bug reports and comments are welcome.

Available states
================

.. contents::
    :local:

``plone``
---------

Installs and configures plone virtualenv and instance from buildout. Requires plone user and group to be present.

``plone.user``
--------------

Ensures the presence of the specified plone user and group running the plone instance.