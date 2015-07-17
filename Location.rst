========
Location
========

==================  =================  =============================
DDSC                NXT
==================  =================  =============================
--                  organisation_code  unique per organisation
created             *created*
*depth*             --                 django-treebeard
description         --
--                  geometry           GeometryField, WGS84
geometry_precision  --                 not used
icon_url            ddsc_icon_url
name                name
*numchild*          --                 django-treebeard
--                  object             for generic relations
--                  *organisation*     lizard-auth-client
owner               --                 resembles NXT's organisation?
*path*              --                 django-treebeard
point_geometry      --                 PointField, ETRS89
real_geometry       --                 not used
relative_location   --                 hardly used
show_on_map         ddsc_show_on_map
uuid                uuid
--                  last_modified
--                  last_modified_by
--                  extra_metadata
==================  =================  =============================

* DDSC has nested Locations (materialized path via django-treebeard), NXT has not.
* DDSC's Location has an unused m2m with LocationType.
* DDSC's point_geometry may have a z dimension.
* DDSC has over 14000 locations (October 2014).
