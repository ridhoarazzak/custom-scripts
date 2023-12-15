---
title: Soil Water Content
parent: Planetary Variables
layout: script
permalink: /planetary-variables/soil-water-content/
nav_exclude: false
---

## Evaluate and visualize
As Soil Water Content is commercial data, brought into Sentinel Hub as Bring Your Own Data, direct EO Browser and Sentinel Playground links are not possible due to the personalized data credentials.

## General description
Soil Water Content (SWC) measures the amount of water in a unit volume of soil, which is crucial information for drought monitoring, water management, and climate risk assessment.

Planet's SWC product provides near-daily measurements at spatial resolutions of 100 m and 1000 m. It is unhindered by clouds and has a long and consistent data record of more than 20 years. Please check [here](https://docs.sentinel-hub.com/api/latest/data/planet/soil-water-content/#available-bands) for a list of available bands.

This script provides 4 outputs. The `default` output is for visualizing SWC in EO Browser. The `index` output is the actual value of the SWC. The `eobrowserStats` and `dataMask` outputs are configured to activate the statistical features in EO Browser.

## Description of representative images
Soil Water Content (L band 100 m) on Sep 30th, 2023 near Hanover, Germany.

![Soil Water Content example](fig/swc.jpg)

## References
- [Product specifications](https://planet.widen.net/s/5xtzljjwgg)
- [Data sheet](https://planet.widen.net/s/cv7bfjhhd5)
- [Sentinel Hub documentation about Soil Water Content](https://docs.sentinel-hub.com/api/latest/data/planet/soil-water-content/)