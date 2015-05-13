## Story Map Example

This project was created for a presentation on Story Maps for the [2015 USFWS Southeast Region GIS Training Workshop](http://www.fws.gov/southeast/gis/gistraining_cookeville_2k15.html) in Cookeville, TN.

This is an example of how to create an interactive and immersive narrative around geographic data with the [Mapbox GL JavaScript Library](https://www.mapbox.com/mapbox-gl/).  As the user scrolls through different stages of my career the map automatically zooms to the location of that particular assignment/institution and highlights a breif narrative.

## Narrative

Updated the different `<section>`s in `index.html` to change the topic titles and narratives.

## Locations

In order to change where the map zooms as you scroll through the topics checkout `js/map/locations.geojson`.  The index property for each of the features in this file correlate to the `data-index` attribute for each `<section>`.  Change the `geometry` coordinates to fit your needs.

## Thanks

This project was inspired by the awesome A List Apart article [Hack your Maps by Young Hahn](http://alistapart.com/article/hack-your-maps) of [Mapbox](mapbox.com).

## [License](https://github.com/USFWS/story-map-template/blob/gh-pages/LICENSE.txt)
