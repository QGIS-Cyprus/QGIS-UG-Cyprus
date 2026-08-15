---
type: "page"
title: "Cyprus in Motion: Animated Maps from Open Data"
subtitle: "Earthquakes, wind, and tourism — visualised in QGIS"
description: "A look at animated QGIS visualisations of open Cyprus datasets — earthquake activity, wind speed and direction, and monthly tourist arrivals."
date: 2022-02-13
draft: false
thumbnail: "https://img.youtube.com/vi/E6mDNhDxjLw/hqdefault.jpg"
---

{{< content-start >}}

# Cyprus in Motion: Animated Maps from Open Data

QGIS's temporal controller and animation tools make it easy to turn a time-stamped dataset into a moving map. A few examples from open Cyprus data:

## Cyprus Earthquakes

An animated map of seismic activity across Cyprus from 1 January to 3 February 2022, plotting each recorded earthquake over time.

<video controls style="max-width: 100%; height: auto; border-radius: 4px;">
  <source src="/video/cyprus-earthquakes-jan-feb-2022.mp4" type="video/mp4">
</video>

## Wind Speed and Direction

A short animation tracking wind speed and direction across Cyprus over the course of a week (8–13 February 2022).

<video controls style="max-width: 100%; height: auto; border-radius: 4px;">
  <source src="/video/cyprus-wind-speed-direction-feb-2022.mp4" type="video/mp4">
</video>

## Monthly Tourist Arrivals

Using data from the Cyprus Statistical Service, an animated visualisation of monthly tourist arrivals throughout 2019 — a simple way to see seasonal patterns that are much harder to read in a spreadsheet.

<video controls style="max-width: 100%; height: auto; border-radius: 4px;">
  <source src="/video/cyprus-tourist-arrivals-2019.mp4" type="video/mp4">
</video>

## COVID-19 Evolution in Cyprus

A walkthrough of building a COVID-19 case animation in QGIS using the Temporal Controller — the same technique behind the maps above, applied to the spread of COVID-19 over time.

{{< youtube E6mDNhDxjLw >}}

**How to create a COVID-19 animation with the QGIS Temporal Controller**

## Try it yourself

All of these use the same core QGIS workflow: a layer with a date/time field, the **Temporal Controller** panel, and the animation export tool. If you have an open Cyprus dataset with a time dimension you'd like help visualising, [get in touch](/about-us/#contact-us) — we're happy to help.

{{< content-end >}}
