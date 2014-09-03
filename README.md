Messenger
=========

A messenger management service.

Features
--------

* Easy place an order.
* Track messenger pickups.
* Track delivery progress in realtime.

Getting start
-------------

To get `Messenger` running you have to:

* Get the code
* Configure local server
* Defining delivery zones and prices
* Create drivers

Code
----

```
mkproject messenger
```

```
git clone https://github.com/wiliamsouza/messenger.git ~/devel/messenger
```

```
pip install requirements_development.txt
```

Dependencies
------------

```
apt-get install spatialite-bin binutils libproj-dev gdal-bin
```

Setup
-----

```
cd messenger
spatialite development.db "SELECT InitSpatialMetaData();"
```

Zones and prices
-----------------

Drivers
-------
