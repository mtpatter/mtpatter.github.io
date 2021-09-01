---
layout: single
permalink: /projects/
title: Tech Projects
header:
  image: /assets/images/telops.jpg
  caption: "Control room at Kitt Peak National Observatory"
---

For my tech projects, I adopt MLOps practices to build robust
and scalable analytics, platforms, and products that are both production
ready and science quality.
I've worked on a lot of cross-disciplinary data analysis projects and enjoy learning
about techniques and tools for ensuring reproducibility in the era
of increasingly growing datasets.

Here are my [publications](https://ui.adsabs.harvard.edu/public-libraries/Hp6pLt5wST6qNm4mzzjfOw){:target="_blank"}, [Google scholar profile](http://scholar.google.com/citations?user=x1kZj8MAAAAJ&hl=en){:target="_blank"}, and [resume and CV](/resume/).

## Science Clouds, "Data Commons", and Streaming Data Pipelines

### - Scalable pipelines for data products
Having worked on enough projects to have made a ton of mistakes, I have a number of
resources for lessons learned, use cases, tutorials, and recommendations for
building data science pipelines and analysis environments.

* [Make a mock “real-time” data stream with Python and Kafka](https://towardsdatascience.com/make-a-mock-real-time-stream-of-data-with-python-and-kafka-7e5e23123582?sk=7ccd7b3383969c2b52c6606c12054c32){:target="_blank"} [[GitHub repo]](https://github.com/mtpatter/time-series-kafka-demo){:target="_blank"} - a tutorial I published on Towards Data Science on how to convert a csv of time series events into a real-time stream with Kafka

* [Machine learning model serving for newbies with MLflow](https://towardsdatascience.com/machine-learning-model-serving-for-newbies-with-mlflow-76f9f0ac3cb2?sk=3fabd570be956c5830591f9ac0fa7991){:target="_blank"} [[GitHub repo]](https://github.com/mtpatter/mlflow-tutorial){:target="_blank"} - a tutorial I published on Towards Data Science on how to serve machine learning models over an API

* [Cloud architecture for the data scientist: Deploying machine learning pipelines to production](https://2020.indycloudconf.com/talks/cloud-architecture-for-the-data-scientist-deploying-machine-learning-pipelines-to-production/){:target="_blank"} [[video]](https://www.youtube.com/watch?v=y0H5Et4hDVQ&list=PLt4L3V8wVnF7cIGxf4nkxScMKcm1Uxvt){:target="_blank"} - a talk I gave at Indy Cloud Conf 2020

* [Building a newsfeed from the Universe: Data streams in astronomy](https://www.confluent.io/kafka-summit-san-francisco-2019/building-a-newsfeed-from-the-universe-data-streams-in-astronomy/){:target="_blank"} - a use case talk I gave at Kafka Summit 2019

* [Streaming Data from the Universe with Apache Kafka](https://www.confluent.io/blog/streaming-data-from-the-universe-with-apache-kafka/){:target="_blank"} - a blog post I wrote for Confluent

* [Data Stream Processing for Newbies with Kafka, KSQL, and Postgres](https://medium.com/high-alpha/data-stream-processing-for-newbies-with-kafka-ksql-and-postgres-c30309cfaaf8?sk=3da652f7ab08ef3a138241569857e110){:target="_blank"} [[GitHub repo]](https://github.com/mtpatter/postgres-kafka-demo){:target="_blank"} - a tutorial on tools for implementing real-time analytics

* [Building a community fountain around your data stream](https://channel9.msdn.com/Events/PyData/Seattle2017/BRK09){:target="_blank"} - a talk I gave at PyData 2017

* [Big data vs the scientist or: How I learned to stop worrying and love the cloud](https://soundcloud.com/loyolachicago/big-data-vs-the-scientist-maria-patterson){:target="_blank"} - a talk I gave at a Meetup for the Chicago ACM group

If you find any of it useful and want to let me know, I always appreciate donations to my Saturday morning fancy coffee fund:

<iframe src="https://github.com/sponsors/mtpatter/card" title="Sponsor mtpatter" height="225" width="600" style="border: 0;"></iframe>

### - Large Synoptic Survey Telescope and Zwicky Transient Facility
I worked for the Large Synoptic Survey Telescope (LSST, now known as the
Legacy Survey of Space and Time carried out at Vera C. Rubin Observatory) in the
data management group on the alert production pipeline team.  The LSST expects to
observe about 10 million changing, or 'transient',
objects per night and will alert astronomers and the public with a large-scale
(~1 TB/night) data stream of these events within 60 seconds of detection.
Our team prototyped the technology for the data distribution system for these
alerts and deployed it successfully in production for use by the Zwicky
Transient Facility (ZTF).  I have written a few technical notes about this work,
which are living documents and continuously updated as work continues:

* [DMTN-028 Benchmarking a distribution system for LSST alerts](https://dmtn-028.lsst.io){:target="_blank"}
* [DMTN-081: Deploying an alert stream mini-broker prototype](https://dmtn-081.lsst.io/){:target="_blank"}
* [DMTN-093: Design of the LSST Alert Distribution System](https://dmtn-093.lsst.io/){:target="_blank"}

And a paper about the [The Zwicky Transient Facility Alert Distribution System](/new-paper-zads/), published in a special
issue of Publications of the Astronomical Society of the Pacific.

### - Open Science Data Cloud
Previously, I was involved with a number of projects in the Open Science Data
Cloud (OSDC) ecosystem.  We described the basic architecture of community science
clouds and use cases for data commons in our paper ['A Case for Data Commons:
Toward Data Science as a Service'](/new-paper-data-commons/),
which appeared in the special issue of Computing in Science and Engineering
magazine on Science as a Service.


### - NOAA
I worked with the Open Commons Consortium (OCC) as Technical Lead for the first stages of the
NOAA Big Data Project (BDP).  We developed a data commons for academic and
scientific researchers working with NEXRAD level 2 radar data.  I worked with
the OCC NOAA Working Group to prototype a two-layer, hash-based, digital ID service that allows
researchers to find and access data in the same way independent of its physical
location, whether
in the OCC commons or in Amazon's public data cloud.
Learn more about our work from my [NOAA BDP partnership update](/ams-noaa-crada-update/)
at the American Meteorological Society annual meeting.

### - NASA
I also worked with Project Matsu, a collaboration between NASA Goddard Space Flight
Center and the Open Commons Consortium,
developing cloud-based applications for the automated processing and analysis of Earth satellite imagery.
Matsu is responsible for tools such as the Namibia Early Warning Flood
Dashboard, which uses ground and satellite measurements to monitor the risk of
flood and subsequent water-borne illness in southern Africa.
I contributed to a Hadoop-based framework to automatically process daily
satellite images from NASA's Earth Observing-1 satellite.
The outline of how the pipeline and several analytics work is in our paper
about the ['Matsu Wheel' for the IEEE Big Data Services and Applications
Conference](http://ieeexplore.ieee.org/document/7474368/){:target="_blank"}.

## Galaxy Formation and Evolution

My dissertation research focused on deep observations of nearby galaxies, as described below.

### - Star formation in galaxy outskirts
The outer disk spiral arms of M81, caused by the interaction with neighboring galaxies M82 and NGC3077, are fertile grounds for exploring star formation in low density environments. The area is characterized by extended cold neutral hydrogen gas (HI) arms and filaments within which are found star forming regions (HII regions of ionized hydrogen) and dwarf galaxies. I analyzed the HII region population over a 1.5 degree field, derived from a Burrell Schmidt H-alpha (ionized hydrogen line) composite supplemented with ARC 3.5-m telescope emission line images of both inner and outer disk HII regions. I focused on studying the luminosities and morphologies of the HII regions and comparing the current massive star formation with the recent and past rates inferred from the stellar populations detected in the outer disk features. I also analyzed abundances for these star forming regions to help determine the origin of outer disk gas. Here you can find a link to [my paper](http://adsabs.harvard.edu/abs/2012MNRAS.422..401P){:target="_blank"}, finding a shallow metallicity gradient for the HII regions of M81 indicating that the outer disk is composed of relatively processed and metal rich gas.

### - Gas accretion
I am a member of the [HALOGAS](http://www.astron.nl/halogas/){:target="_blank"} collaboration. The Hydrogen Accretion in LOcal GAlaxieS (HALOGAS) survey aims to investigate cold gas accretion in a sample of 22 neutrally-selected nearby spiral galaxies with 120 hours of integrated observation time at 21 cm for each target. The data are sensitive enough to study faint neutral hydrogen in the galaxy outskirts and to search for halogas and for possible accreting gas clouds. I worked on modeling the HI (cold hydrogen) for a few of these galaxies and studied the correlation between features in the HI gas and features detected in GALEX UV and H-alpha star formation tracers.

### - Stellar streams and companions
Deep and wide-field optical imaging is essential to understand the role of accretion and the source of accreting gas and new material in galaxies. I was the PI for an observing campaign to image the HALOGAS Survey sample of galaxies in broadband and emission line filters with the Kitt Peak National Observatory's 4-meter telescope, in order to search for faint companions and stellar stream features around the galaxies. We compared these images with our very deep HI data to better understand the process of galaxy growth.
My observations are deep enough to successfully recover faint star formation and old stellar streams in several galaxies, including, for example [NGC 4414](http://adsabs.harvard.edu/abs/2014A%26A...566A..80D){:target="_blank"} (which has a huge, beautiful faint shell!), [NGC 3198](http://adsabs.harvard.edu/abs/2013A%26A...554A.125G){:target="_blank"}, and [NGC 5023](http://adsabs.harvard.edu/abs/2013MNRAS.434.2069K){:target="_blank"}.  You can also find some really cool downloadable images from my dissertation featured by NSF’s National Optical-Infrared Astronomy Research Laboratory on my [media page](https://mtpatter.github.io/media/).

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
paper about the [Matsu Wheel](http://ieeexplore.ieee.org/document/7474368/){:target="_blank"}.

### - Neighbor-based bootstrapping
I also developed a Monte Carlo based algorithm called Neighbor-based
Bootstrapping (NB2) that can be used to quantify geospatial autocorrelation and
tailored to be more sensitive to either tight cluster patterns or broader less
peaked patterns. I applied this algorithm to analyze electronic medical records (EMR) data across the United States to
look for geospatial patterns and possible environmental factors influencing the incidence of disease and disease pairs.  The results were published in the journal "Big Data" Vol. 5, No. 3, Sep 2017.  Read the paper [here](https://arxiv.org/abs/1703.01692){:target="_blank"}.
