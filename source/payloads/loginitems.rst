.. _payloadtype-com.apple.loginitems.managed:

Login Items
===========

The login items payload manages the login items normally found in a user's **Login Items** tab in the
**Users and Groups** System Preference pane.

It shares a lot of functionality with the ``loginwindow`` domain. In fact the same code handles both, with the exception
that the loginwindow domain applies at the system level only - *NEEDS VERIFICATION*.

.. contents::

Summary
-------

.. pfmheader:: /_static/manifests/com.apple.loginitems.managed manifest.plist

Keys
----

.. pfmkey:: AutoLaunchedApplicationDictionary-managed /_static/manifests/com.apple.loginitems.managed manifest.plist


Items
^^^^^

Each item may contain these keys

.. pfm:: /_static/manifests/com.apple.loginitems.managed manifest.plist
    :key: AutoLaunchedApplicationDictionary-managed:AutoLaunchedApplicationItem



