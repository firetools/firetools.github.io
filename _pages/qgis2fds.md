---
layout: single
permalink: /qgis2fds/
hidden: true
title: "gis2fds<span style='color: #bcbcbc'> = QGIS + FDS</span>"
header:
  overlay_image: /assets/images/qgis2fds.png
  overlay_filter: 0.6
  actions:
    - label: "<i class='fas fa-play'></i> Quickstart"
      url: "https://github.com/firetools/qgis2fds/wiki/Quickstart"
    - label: "<i class='fa-solid fa-download'></i> Install"
      url: "https://github.com/firetools/qgis2fds/wiki/Install"
    - label: "<i class='fa-brands fa-readme'></i> Read the doc"
      url: "https://github.com/firetools/qgis2fds/wiki"
    - label: "<i class='fa-solid fa-question'></i> Ask a question"
      url: "https://github.com/firetools/qgis2fds/discussions"
    - label: "<i class='fa-solid fa-bug'></i> Submit an issue"
      url: "https://github.com/firetools/qgis2fds/issues"
excerpt: >
  An open source QGIS plugin that generates terrain elevation and landuse for NIST FDS wildfire or atmospheric pollutants dispersion simulations.
toc: true
gallery:
  - url: /assets/images/qgis2fds-preview/1.jpg
    image_path: /assets/images/qgis2fds-preview/1.jpg
    alt: "Golden Gate area"
    title: "Start from the Golden Gate area"
  - url: /assets/images/qgis2fds-preview/2.png
    image_path: /assets/images/qgis2fds-preview/2.png
    alt: "Plan your simulation domain"
    title: "Plan your simulation domain"
  - url: /assets/images/qgis2fds-preview/3.png
    image_path: /assets/images/qgis2fds-preview/3.png
    alt: "Import digital terrain elevation data"
    title: "Import digital terrain elevation data"
  - url: /assets/images/qgis2fds-preview/4.png
    image_path: /assets/images/qgis2fds-preview/4.png
    alt: "Import landuse data"
    title: "Import landuse data"
  - url: /assets/images/qgis2fds-preview/5.png
    image_path: /assets/images/qgis2fds-preview/5.png
    alt: "Run the qgis2fds plugin"
    title: "Run the qgis2fds plugin"
  - url: /assets/images/qgis2fds-preview/6.png
    image_path: /assets/images/qgis2fds-preview/6.png
    alt: "The plugin samples the data"
    title: "The plugin samples the data"
  - url: /assets/images/qgis2fds-preview/7.png
    image_path: /assets/images/qgis2fds-preview/7.png
    alt: "Run your FDS case, or import it into BFDS for further customization"
    title: "Run your FDS case, or import it into BFDS for further customization"
---

## qgis2fds at a glance

**qgis2fds** is an experimental project still subject to huge modifications.
{: .notice--warning}

{% include gallery id="gallery" layout="third" caption="Click to browse." %}

## Terrain and landuse for FDS simulations

qgis2fds allows you to seamlessly prepare **terrain elevation** and **land-use data** for wildfire and atmospheric pollutant dispersion simulations, directly from within QGIS.

You can:

- extract and process **digital elevation models** (DEM) to generate realistic terrain for FDS domains;

- incorporate **land-use and vegetation layers** to define surface characteristics relevant to fire spread or pollutant transport;

- **export** simulation-ready input files, eliminating manual preprocessing and ensuring consistency with geospatial sources.

Designed for **fire safety engineers**, **environmental scientists**, and **students**, qgis2fds leverages the powerful GIS capabilities of QGIS to streamline the setup of complex simulations in FDS.

## What is QGIS?

[QGIS](https://qgis.org/) is a free and open-source **geographic information system** (GIS) used to view, edit, analyze, and visualize geospatial data. It supports a wide range of vector, raster, and database formats, making it a powerful tool for mapping and spatial analysis.

## License

QGIS and qgis2fds are both **free software**.

qgis2fds was released under the terms of the GNU General Public License. It is distributed in the hope that it will be useful, but without any warranty.

## Financing

![logo-maeci](/assets/images/logo-maeci.jpeg){: .align-left}

During 2020–2021, the development was supported by a **grant** from the [Italian Ministry of Foreign Affairs and International Cooperation](https://www.esteri.it/it/).

By the research project WUIFI-21 (High fidelity computational fluid dynamics modeling of forest fires for Wildland-Urban Interface communities resilience and protection) the participating organizations intended to extend the capabilities of FDS on the prediction of **wildland-urban interface fires** propagation.
{: .notice--info}