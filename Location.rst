========
Location
========

==================  ==============
DDSC                NXT
==================  ==============
--                  code
created             *created*
*depth*             --
description         --
--                  geometry
geometry_precision  --
icon_url            --
name                name
*numchild*          --
--                  object
--                  *organisation*
owner               --
*path*              --
point_geometry      --
real_geometry       --
relative_location   --
show_on_map         --
uuid                --
==================  ==============

* DDSC has nested Locations (via django-treebeard), NXT has not.
* DDSC uses ETRS89 as a reference system, NXT WGS84.
* In DDSC, Location has an unused m2m with LocationType.
* DDSC's owner resembles NXT's organisation?
* DDSC's geometry_precision is unused.
* DDSC's real_geometry is unused.
* DDSC's relative_location is hardly used.
