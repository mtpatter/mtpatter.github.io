---
layout: single
title: Paper on ZTF alerts published
excerpt: "Our new paper 'The Zwicky Transient Facility Alert Distribution System' was published in Publications of the Astronomical Society of the Pacific."
modified: 2018-11-27
---


Our new paper 'The Zwicky Transient Facility Alert Distribution System' was published in Publications of the Astronomical Society of the Pacific.

This paper talks about the design and technology behind the alert system for ZTF, which is also a prototype for the upcoming Large Synoptic Survey Telescope.

Abstract:

> The Zwicky Transient Facility (ZTF) survey generates real-time alerts for optical transients, variables, and moving objects discovered in its wide-field survey. We describe the ZTF alert stream distribution and processing (filtering) system. The system uses existing open-source technologies developed in industry: Kafka, a real-time streaming platform, and Avro, a binary serialization format. The technologies used in this system provide a number of advantages for the ZTF use case, including (1) built-in replication, scalability, and stream rewind for the distribution mechanism; (2) structured messages with strictly enforced schemas and dynamic typing for fast parsing; and (3) a Python-based stream processing interface that is similar to batch for a familiar and user-friendly plug-in filter system, all in a modular, primarily containerized system. The production deployment has successfully supported streaming up to 1.2 million alerts or roughly 70 GB of data per night, with each alert available to a consumer within about 10 s of alert candidate production. Data transfer rates of about 80,000 alerts/minute have been observed. In this paper, we discuss this alert distribution and processing system, the design motivations for the technology choices for the framework, performance in production, and how this system may be generally suitable for other alert stream use cases, including the upcoming Large Synoptic Survey Telescope.


Read the paper here:
['The Zwicky Transient Facility Alert Distribution System'](http://iopscience.iop.org/article/10.1088/1538-3873/aae904/) by Maria T. Patterson, Eric C. Bellm, Ben Rusholme, Frank J. Masci, Mario Juric, K. Simon Krughoff, V. Zach Golkhou, Matthew J. Graham, Shrinivas R. Kulkarni, and George Helou.

Or contact me for a personal copy.
