---
layout: page
title: Vector tiles
permalink: /the-basics/vector/
---

# Vector tiles

With vector tiles, what typically happens is this:

* Using osm data, someone creates a series of small databases, one for each geographical area and zoom level.  Different sets of tiles can be created for different purposes, and what goes in each one is determined by the "schema" of the vector tile set.
* Someone also creates a map style, which determines how the things in the schema should appear on screen.
* Your web page includes some script code that can read the map style and the vector tiles themselves, and can display a map onscreen.  There are APIs you can call from iOS and Android native apps too.

## Choosing a provider (or doing it yourself)

There are many different providers of vector tiles, web map styles and script libraries.  Some of the providers offer a 'mostly hosted' service where everything apart from the link on your website to their script is hosted by them, some offer you the chance to self-host everything, and some offer options in between.

The vector tile pages of this guide will describe fully self hosted options, but will also refer to the other options that are available.

## Choosing a schema

Many vector tile schemas for OSM data already exist, such as [Shortbread](https://shortbread-tiles.org/schema/) and [OpenMapTiles](https://openmaptiles.org/schema/). If you use an existing schema you will then have several existing map styles to choose from - you won't have to create your own. If you do need to create your own schema, you'll also need to create your own style AND host your own vector tiles.

## Choosing a map style

qqq
