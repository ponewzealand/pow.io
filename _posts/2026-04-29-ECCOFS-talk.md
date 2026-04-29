---
title: Recent developments in data assimilation and downscaling; The North American East Coast Community Ocean Forecast System (ECCOFS).
author: wilkin
date: 2026-04-30 00:00:00 +0000
categories: [Coastal NZ]
tags: [modelling,oceanography]
render_with_liquid: false
comments: true
---


## Abstract

A data assimilating ocean forecast system whose domain encompasses the East Coast of North America and Intra-Americas Sea from the Grand Banks to Venezuela is being developed for eventual transition to operations by the U.S. National Ocean Service. Each day the system generates a new 5-day forecast of sea level, ocean currents, salinity and temperature for the full 3-dimensional water column. Observations assimilated include satellite sea level, temperature and salinity, surface velocity from land-based radars, and in situ temperature and salinity from moorings, drifters, profiling floats, autonomous vehicles, ships of opportunity, and sensors affixed to fishing gear and animal tags. The system employs several recent developments in Regional Ocean Modeling System (ROMS) 4-Dimensional Variational (4D-VAR) data assimilation (DA), including space and time-average observation operators, Rossby-radius dependent scales in the background error covariance, and mixed resolution DA. In ECCOFS Mixed Resolution 4D-VAR, the nonlinear forecast is computed at 3-km resolution, but the so-called inner loops of 4D-VAR are run at lower 6-km resolution to reduce wall-clock run-time in operations while still respecting the resolution of the observing networks. The system can run on Amazon Web Services (AWS) commercial cloud or in-house High Performance Compute clusters. In the spirit of open-source open-science modeling, the ECCOFS project is making available software tools for (i) users and stakeholders to easily configure 1-way downscaling nests for local applications, and (ii) cloud-native pre-processing of model inputs from sources in the AWS Open Data Registry, NASA Earthdata Cloud, and Copernicus Marine Data Store.

## When

Suscribe to the mailing list to receive an invite to this talk
