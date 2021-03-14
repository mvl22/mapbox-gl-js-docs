---
title: Display a popup on click
description: When a user clicks a symbol, show a popup containing more information.
topics:
  - Controls and overlays
thumbnail: popup-on-click
contentType: example
layout: example
language:
- JavaScript
products:
- Mapbox GL JS
prependJs:
- "import Example from '../../components/example';"
- "import html from './popup-on-click.html?code';"
- "import iframe from './popup-on-click.html?iframe';"
---

This example uses the built-in Mapbox GL JS [`Popup`](/mapbox-gl-js/api/markers/#popup) method to create popups displaying information about three places.

It uses [`addSource`](/mapbox-gl-js/api/map/#map#addsource) and [`addLayer`](/mapbox-gl-js/api/map/#map#addlayer) to add three new point features to the map in a layer called `places`, using `icon` images in the [Mapbox Light](https://docs.mapbox.com/api/maps/styles/#mapbox-styles) style to represent them.

Then it uses Mapbox GL JS [`Map` events](/mapbox-gl-js/api/map/#map-events) to customize the appearance of the cursor and display `Popup` objects when the user clicks on a feature in the `places` layer.

{{ <Example html={html} iframeSrc={iframe} {...this.props} /> }}
