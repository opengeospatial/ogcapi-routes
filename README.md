# Routing SWG

This GitHub repository contains [OGC](http://opengeospatial.org)'s proposed standards for routing.

The editor's drafts of the specifications can be found at

* [OGC API - Routes - Part 1: Core](https://docs.ogc.org/DRAFTS/21-000.html)
* [OGC Route Exchange Model](https://docs.ogc.org/DRAFTS/21-001.html)

[OGC API standards](https://ogcapi.ogc.org) define modular API building blocks to spatially enable Web APIs in a consistent way. [OpenAPI](http://openapis.org) is used to define the reusable API building blocks with responses in JSON and HTML.

The OGC API family of standards is organized by resource type. OGC API Routes specifies API building blocks for interacting with routes.

The work on the API started in the [OGC Open Routing Pilot](https://www.ogc.org/projects/initiatives/routingpilot).

## Overview

In addition to the resources provided through inheritance from [OGC API - Common](https://ogcapi.ogc.org/common), the following resources are also provided by [OGC API - Routes](https://ogcapi.ogc.org/routes):

```
POST /routes
```
Compute a new route.

```
GET /routes
```

Fetch routes.

```
GET /routes/{routeId}
```
Fetch a route.

```
DELETE /routes/{routeId}
```

Delete a route.

```
GET /routes/{routeId}/definition
```

Fetch the definition of a route.

## Communication

Most of the work on the specification takes place in [GitHub issues](https://github.com/opengeospatial/ogcapi-routes/issues),
so browse there to get a good idea of what is happening, as well as past decisions.

## Additional information

This repository contains draft content for both:

* [OGC API - Routes - Part 1: Core](https://docs.ogc.org/DRAFTS/21-000.html)
* [OGC Route Exchange Model](https://docs.ogc.org/DRAFTS/21-001.html)

## Building

To generate the HTML versions of the standards from this repository yourself, ensure that you have [Ruby](https://www.ruby-lang.org/en/) and
[Asciidoctor](https://asciidoctor.org/) set up and [installed](https://asciidoctor.org/docs/#get-started-with-asciidoctor).
Then run:

```bash
asciidoctor api/standard/21-000.adoc
asciidoctor rem/standard/21-001.adoc
```

The resulting HTML files will be built in the same directory as the AsciiDoc file, e.g. as `api/standard/21-000.html`.

## Contributing

The contributor understands that any contributions, if accepted by the OGC Membership, shall be incorporated into OGC standards documents and that all copyright and intellectual property shall be vested to the OGC.

The OGC Routing Standards Working Group (SWG) is the group at OGC responsible for the stewardship of the standard, but is working to do as much work in public as possible.

* [Open issues](https://github.com/opengeospatial/ogcapi-routes/issues)
* [Copy of License Language](https://raw.githubusercontent.com/opengeospatial/ogcapi-routes/master/api/LICENSE)

For more information, see [CONTRIBUTING.md](CONTRIBUTING.md).

Pull Requests from contributors are welcomed. However, please note that by sending a Pull Request or Commit to this GitHub repository, you are agreeing to the terms in the Observer Agreement https://portal.ogc.org/files/?artifact_id=96216
