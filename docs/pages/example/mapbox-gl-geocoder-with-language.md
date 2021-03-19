---
title: Localize the geocoder to a given language
description: Localize the mapbox-gl-geocoder control to set the UI language and improve result relevance in that language.
topics:
  - Geocoder
thumbnail: mapbox-gl-geocoder-with-language
contentType: example
layout: example
language:
- JavaScript
products:
- Geocoding API
- Mapbox GL JS
prependJs:
- "import Example from '../../components/example';"
- "import html from './mapbox-gl-geocoder-with-language.html?code';"
- "import iframe from './mapbox-gl-geocoder-with-language.html?iframe';"
---

This example localizes the [mapbox-gl-geocoder](https://github.com/mapbox/mapbox-gl-geocoder) control by setting the UI language and improving places search results relevant in that language.

The `mapbox-gl-geocoder` plugin uses the [Mapbox Geocoding API](https://docs.mapbox.com/api/search/geocoding/) to enable places search.

{{ <Example html={html} iframeSrc={iframe} {...this.props} /> }}
