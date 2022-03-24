# ldproxy

Routing API for the OGC Routing Pilot Sprint https://rps.ldproxy.net/

ldproxy supports the current drafts of OGC API - Routes - Part 1: Core and OGC Route Exchange Model starting with version 3.2.

In addition to the requirements of the candidate standards, the ldproxy implementations also supports:

* Coordinate reference systems other than WGS 84 longitude/latitude;
* For 3D data, ascent and descent information is derived from the route geometry, too;
* A HTMl form is supported to allow creating a routing request in the browser.

Currently only SQL backends are supported. The implementation has been tested with PostgreSQL with the pgRouting extension.
