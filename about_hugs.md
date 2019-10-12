---
layout: splash
title: About
permalink: /about/
header:
  overlay_color: "#b01b2e"
  overlay_image: /assets/images/chimney-exhaust-gases-factory.jpg
---
The rapid growth in remotely sensed and in situ greenhouse gas (GHG) observations will dramatically improve our understanding of the drivers of change in atmospheric radiative forcing. However, the volume and diversity of available data presents a range of challenges. For example, efficient, near-real-time sharing and inter-comparison of data and model outputs is hampered by strict institutional firewalls and, in some cases, lack of computational expertise by data providers and users.

The data span a range of scales and sample different parts of the atmosphere, so inter-comparison and interpretation requires the use of Chemical transport models (CTMs); the “inverse” statistical methods for inferring fluxes using the data and models are computationally intensive and technically challenging to implement. 

At present, these limitations mean that GHG flux estimates are generally only carried out on a case-by-case basis for specific research projects, each requiring intensive investigator effort. To address these challenges, we present a feasibility study demonstrating a cloud-based data analysis “hub” for the GHG community. We have brought together measurement, modelling, statistical and cloud-computing expertise to build the architecture for a cloud framework that will streamline the process for data sharing, validation, analysis and visualisation. 

Using open-source tools, this framework will be extensible by GHG scientists to carry out the full workflow from data acquisition to operational GHG flux estimation. Such a system will allow us to more effectively integrate data from multiple sources and ultimately provide stakeholders and researchers with more rapid, more robust estimates of GHG sources and sinks. 

## Technologies

This platform builds on the expertise used to create the [Acquire](https://github.com/chryswoods/acquire) and [Cluster-in-the-Cloud](https://cluster-in-the-cloud.readthedocs.io/en/latest/) architecture developed within the Advanced Computing Research Centre at the University of Bristol.

<img src="/assets/images/technologies.png" alt="drawing" width="1080"/>

The HUGS Hub, a JupyterHub platform from which to interact with the platform, is powered using a customised Docker container and managed using Kubernetes. The platform is currently hosted on the Oracle Cloud platform but due to the open-source technologies used the platform is provider agnostic and may be run on any compatible cloud platform. Using the HUGS Hub it will be possible to upload, analyse and run simulations using the inherently scalable nature of the cloud.

The video below is an example of the power of utilising a Jupyter Notebook interface for data analysis and processing.

{% include youtube.html id='pnvjtGi5nPA' %}