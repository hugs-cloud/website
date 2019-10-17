---
layout: splash
permalink: /
header:
  overlay_color: "#b01b2e"
  overlay_image: /assets/images/air_quality.jpg
excerpt: >
  HUb for greenhouse Gas data Science
---
HUGS is a cloud-based data analysis "hub" for greenhouse gas measurements, modelling and data analysis, funded as a NERC ["Constructing a Digital Environment"](https://nerc.ukri.org/innovation/activities/environmentaldata/digitalenv/) feasibility study. We aim to streamline the process for greenhouse gas data sharing, analysis and visualisation and add value through automated processes such as atmospheric chemistry transport model runs associated with data.

## Challenges

Current challenges when dealing with greenhouse gas data include:
- a wide and diverse range of measurements spanning a range of scales (e.g., urban to global)
- a range of non-standard formats leading in difficulty in inter-comparing datasets
- institutional firewalls forming a barrier to sharing of data
- case-by-case data analysis on a subset of all available data
- lack of reproducibility and transparency in the emissions evaluation process

## Solutions

The HUGS platform aims to solve these challenges by providing a platform for greenhouse gas data analysis. It will allow comparison of data with vital ancillary information such as atmospheric model output, emissions inventories, and mapping tools. The platform will also provide key analysis methods and functionality. We do not plan on creating another long-term data storage repository, we want HUGS to be a platform that facilitates sharing and analysis of archived greenhouse gas data.

HUGS is built on open source tools such as [xarray](http://xarray.pydata.org/en/stable/) and [Jupyter notebooks](https://jupyter.org).

## Interface

Interaction with the data and associated products to plot and interpret will be facilitated via a simple web interface with more functionality available via Jupyter notebooks.

<div style="text-align: center">
<img src="/assets/images/HUGS_notebook_interface.jpg" alt="drawing" width="1080"/>
</div>

## Visualisation

HUGS will allow users to run complex simulations on demand, allowing creation of striking visualisations that help transfer knowledge effectively.

<div style="text-align: center">
<video height="400" muted loop autoplay controls>
  <source src="/assets/video/UK_footprint_movie.m4v" type="video/mp4">
</video>
</div>
<div style="text-align: center">
<b>Video 1.</b> Footprints calculated using the Met Office NAME model for 6 sites in the UK and the Republic of Ireland in March 2014.<br/>
Credit: Dr Matthew Rigby, ACRG, University of Bristol
</div>

## Prototype

To use a prototype of the platform please visit the [Registration]({{ site.baseurl }}{% link registration.md %}) page and submit your details. You will then be emailed a username and password to login to the [HUGS Hub](https://hub.hugs-cloud.com) that allows interaction with the HUGS platform through a simple
Jupyter Notebook interface.

To participate or for more information please contact [Dr. Matt Rigby](mailto:matt.rigby@bristol.ac.uk).
