# Ali Basbeth

Geospatial data analyst and M.S. in Information Systems candidate at the University of Washington Foster School of Business.

**Portfolio:** [lostgovernment.github.io](https://lostgovernment.github.io)

This repository holds the source code for my portfolio site.

## About

I earned my B.A. in Geography (Data Science track) from the University of Washington in 2022, then spent three years as a LiDAR analyst at GIS Surveyors Inc., where I standardized QA/QC workflows and wrote Python automation for large geospatial datasets. I'm now pursuing an M.S. in Information Systems (expected June 2027) and looking for data analytics, BI engineering, and data engineering roles.

## Featured projects

### Bellevue Incident Map

An interactive map of about 373,000 Bellevue Police calls for service from 2021 to 2026, shown as hexagons or by block, with date and category filters, trend charts, and a custom basemap.

**Built with:** MapLibre GL JS, JavaScript, GeoJSON, City of Bellevue Open Data, OpenStreetMap
[Live map](https://lostgovernment.github.io/bellevue-incident-map/) · [Source](https://github.com/LostGovernment/bellevue-incident-map)

### COVID-19 US Web Maps

Two interactive maps of 2020 COVID-19 cases by US county: a proportional-symbol map of case counts and a choropleth of rates per 100,000 residents.

**Built with:** Mapbox GL JS, JavaScript, GeoJSON, NYT COVID-19 data, US Census data
[Case counts](https://htmlpreview.github.io/?https://github.com/LostGovernment/us-covid-2020-geog458/blob/main/map1.html) · [Case rates](https://htmlpreview.github.io/?https://github.com/LostGovernment/us-covid-2020-geog458/blob/main/map2.html) · [Source](https://github.com/LostGovernment/us-covid-2020-geog458)

### Geo-Tagged Tweet Analysis

Tweets collected through the Twitter API in an early-morning and an afternoon window, compared with maps of where people tweeted and word clouds of what they tweeted about.

**Built with:** Python, Pandas, Twitter API, Jupyter Notebook
[Notebook](https://github.com/LostGovernment/lab2-expert-octo-palm-tree/blob/main/%281%2902_geosearch.ipynb) · [Source](https://github.com/LostGovernment/lab2-expert-octo-palm-tree)

### Custom Basemap & Map Tile Design

Four basemaps designed in Mapbox Studio and published as raster map tiles, including a Washington broadband speed-test map and a wetlands and parks map around Bellevue.

**Built with:** Mapbox Studio, Mapbox GL JS, QGIS
[Live demo](https://lostgovernment.github.io/Map-Tiles-Design-Lab4-geog458/) · [Source](https://github.com/LostGovernment/Map-Tiles-Design-Lab4-geog458)

### Malaria Risk Mapping

A risk map of where malaria-carrying mosquitoes could survive in Kenya, classified by average March temperature and excluding land above 1,500 meters.

**Built with:** QGIS
[Full-resolution map](images/Malaria%20Map%203.png)

More projects: [github.com/LostGovernment](https://github.com/LostGovernment?tab=repositories)

## Experience

**Senior LiDAR Analyst**, GIS Surveyors Inc. (Sep 2022 – Jan 2026)

- Built standardized QA/QC workflows that reached 100% QC accuracy and cut review time by 50% across 250 GB+ of weekly deliverables.
- Wrote Python scripts and MicroStation macros that automated repetitive tasks on long-term client projects.
- Managed QC reporting for project managers and trained new hires in QA/QC workflows.

## About this site

The site is plain HTML, CSS, and JavaScript in a single `index.html`, with no frameworks or build step. GitHub Pages serves it from the `main` branch.

```
index.html          the whole site: markup, styles, and scripts
images/optimized/   web-sized images shown on the page
images/             original full-resolution images
```

To view it locally, open `index.html` in a browser, or run a local server from this folder:

```
python3 -m http.server
```

and visit `http://localhost:8000`.

## Contact

- Email: [basbethali@gmail.com](mailto:basbethali@gmail.com)
- LinkedIn: [linkedin.com/in/ali-basbeth](https://www.linkedin.com/in/ali-basbeth/)
- GitHub: [github.com/LostGovernment](https://github.com/LostGovernment)
