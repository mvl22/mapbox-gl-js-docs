---
title: Use the geocoder without a map
description: Use the mapbox-gl-geocoder control to search for places using Mapbox Search API without an associated map view.
topics:
  - Geocoder
thumbnail: mapbox-gl-geocoder-no-map
contentType: example
layout: example
language:
- JavaScript
products:
- Geocoding API
- Mapbox GL JS
prependJs:
- "import Example from '../../components/example';"
- "import html from './mapbox-gl-geocoder-no-map.html?code';"
- "import iframe from './mapbox-gl-geocoder-no-map.html?iframe';"
---

This example uses the [mapbox-gl-geocoder](https://github.com/mapbox/mapbox-gl-geocoder) control plugin to enable users to search for places with the [Mapbox Geocoding API](https://docs.mapbox.com/api/search/geocoding/) without an associated map view.

{{ <Example html={html} iframeSrc={iframe} {...this.props} /> }}
