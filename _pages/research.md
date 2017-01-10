---
layout: single
permalink: /research/
title: Research 
header:
  image: /assets/images/gummy.jpg
---

I have a strong interest in adapting the DevOps culture and practices to enable
robust scientific research. 
I enjoy engaging in cross-disciplinary scientific data analysis and learning
about techniques and tools for ensuring reproducibility in research in the era
of increasingly growing datasets.  I also enjoy outreach and working on effective science communication.


<br>Here is my [SAO/NASA ADS publications query](http://adsabs.harvard.edu/cgi-bin/nph-abs_connect?library&libname=my+publications&libid=4f29dfc54b) and my [Google scholar profile](http://scholar.google.com/citations?user=x1kZj8MAAAAJ&hl=en).

## Science Clouds and Pipelines

### - LSST 
I'm currently working with the LSST's data management group on the alert
production pipeline team.  The LSST expects to observe about 10,000 transient
objects per visit and will aim to send out public alerts on these events within
60 seconds.  I'm working on the technology for the alert distribution system.

### - OSDC
Previously, I was involved with a number of projects in the Open Science Data
Cloud ecosystem.  We described the basic architecture of community science
clouds and use cases for data commons in our paper ['A Case for Data Commons:
Toward Data Science as a Service'](http://dx.doi.org/10.1109/MCSE.2016.92),
which appeared in the special issue of Computing in Science and Engineering
magazine on Science as a Service.

### - NASA
I worked with Project Matsu, a collaboration between NASA Goddard Space Flight
Center and the Open Commons Consortium,
developing cloud-based applications for the automated processing and analysis of Earth satellite imagery.
Matsu is responsible for tools such as the Namibia Early Warning Flood
Dashboard, which uses ground and satellite measurements to monitor the risk of
flood and subsequent water-borne illness in southern Africa.
I contributed to a Hadoop-based framework to automatically process daily
satellite images from NASA's Earth Observing-1 satellite.
The outline of how the pipeline and several analytics work is in our paper
about the ['Matsu Wheel' for the IEEE Big Data Services and Applications
Conference](http://ieeexplore.ieee.org/document/7474368/).

### - NOAA
I also worked with the Open Commons Consortium on the early stages of the
NOAA Big Data Project.  The OCC developed a data commons for academic and
scientific researchers working with NEXRAD level 2 radar data.  I worked with
the OCC NOAA Working Group to prototype a two-layer, hash-based, digital ID service that allows
researchers to find and access data in the same way independent of its physical
location, whether
in the OCC commons or in Amazon's public data cloud.


## Galaxy Formation and Evolution

My dissertation research focused on deep observations of nearby galaxies, as described below. 

### - Star formation in galaxy outskirts
The outer disk spiral arms of M81, caused by the interaction with neighboring galaxies M82 and NGC3077, are fertile grounds for exploring star formation in low density environments. The area is characterized by extended cold neutral hydrogen gas (HI) arms and filaments within which are found star forming regions (HII regions of ionized hydrogen) and dwarf galaxies. I analyzed the HII region population over a 1.5 degree field, derived from a Burrell Schmidt H-alpha (ionized hydrogen line) composite supplemented with ARC 3.5-m telescope emission line images of both inner and outer disk HII regions. I focused on studying the luminosities and morphologies of the HII regions and comparing the current massive star formation with the recent and past rates inferred from the stellar populations detected in the outer disk features. I also analyzed abundances for these star forming regions to help determine the origin of outer disk gas. Here you can find a link to my paper, finding a [shallow metallicity gradient for the HII regions of M81 indicating that the outer disk is composed of relatively processed and metal rich gas](http://adsabs.harvard.edu/abs/2012MNRAS.422..401P).

### - Gas accretion
I am a member of the [HALOGAS](http://www.astron.nl/halogas/) collaboration. The Hydrogen Accretion in LOcal GAlaxieS (HALOGAS) survey aims to investigate cold gas accretion in a sample of 22 neutrally-selected nearby spiral galaxies with 120 hours of integrated observation time at 21 cm for each target. The data are sensitive enough to study faint neutral hydrogen in the galaxy outskirts and to search for halogas and for possible accreting gas clouds. I worked on modeling the HI (cold hydrogen) for a few of these galaxies and studied the correlation between features in the HI gas and features detected in GALEX UV and H-alpha star formation tracers.

### - Stellar streams and companions
Deep and widefield optical imaging is essential to understand the role of accretion and the source of accreting gas and new material in galaxies. I was the PI for an observing campaign to image the HALOGAS Survey sample of galaxies in broadband and emission line filters with the Kitt Peak National Observatory's 4-meter telescope, in order to search for faint companions and stellar stream features around the galaxies. We compared these images with our very deep HI data to better understand the process of galaxy growth.
My observations are deep enough to successfully recover faint star formation and old stellar streams in several galaxies, including, for example [NGC 4414](http://adsabs.harvard.edu/abs/2014A%26A...566A..80D) (which has a huge, beautiful faint shell!), [NGC 3198](http://adsabs.harvard.edu/abs/2013A%26A...554A.125G), and [NGC 5023](http://adsabs.harvard.edu/abs/2013MNRAS.434.2069K).

## Algorithms

### - Analytic wheels
An analytic wheel is designed to be able to support scanning queries using
cloud computing applications. A scanning query processes all, or most, of the
data in a database or data repository. In contrast, standard queries typically
process a relatively small percentage of the data. The wheel is a framework in
which multiple scanning queries are grouped together and processed in turn,
over chunks of data from the database or repository. Over time, the framework
brings all data to each group of scanning queries. With this approach,
contention and the overall time to process all scanning queries can be reduced.
We wrote about an application of an analytic wheel to satellite data in our
paper about the [Matsu Wheel](http://ieeexplore.ieee.org/document/7474368/).

### - Neighbor-based bootstrapping
I also developed a Monte Carlo based algorithm called Neighbor-based
Bootstrapping (NB2) that can be used to quantify geospatial autocorrelation and
tailored to be more sensitive to either tight cluster patterns or broader less
peaked patterns. I applied this algorithm to analyze electronic medical records (EMR) data across the United States to 
look for geospatial patterns and possible environmental factors influencing the incidence of disease and disease pairs.

