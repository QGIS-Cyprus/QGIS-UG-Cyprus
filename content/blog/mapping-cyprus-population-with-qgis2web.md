---
type: "page"
title: "Mapping Cyprus' Population with QGIS and qgis2web"
subtitle: "Turning Statistical Service census data into an interactive map"
description: "An interactive map and table of Cyprus' 2021 population, built in QGIS from Statistical Service preliminary results and published on the web with the qgis2web plugin."
date: 2023-08-16
draft: false
thumbnail: "/img/cyprus-population-map-2021.jpg"
---

{{< content-start >}}

# Mapping Cyprus' Population with QGIS and qgis2web

Using preliminary results from the Cyprus Statistical Service, this project maps population trends across Cyprus at the enumeration-district level — built entirely in QGIS and published to the web with the [qgis2web](https://plugins.qgis.org/plugins/qgis2web/) plugin, no server-side code required.

{{< content-image src="/img/cyprus-population-map-2021.jpg" alt="Interactive choropleth map of Cyprus population by district, built with QGIS and qgis2web" >}}

- 🗺️ [Interactive map](https://cypruspopulation-map.netlify.app/) — explore the geographical distribution of the population
- 📊 [Detailed table](https://cypruspopulation-table.netlify.app/) — figures for 2011 and 2021 side by side

Built with QGIS, Leaflet, and open data from [cystatdb.cystat.gov.cy](https://cystatdb.cystat.gov.cy/) and [data.gov.cy](https://data.gov.cy/).

It's a good example of what's possible with QGIS and open government data — no proprietary web-mapping stack needed, just QGIS, a free plugin, and a static host.

{{< content-end >}}
