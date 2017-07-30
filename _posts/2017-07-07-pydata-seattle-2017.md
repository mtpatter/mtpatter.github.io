---
layout: single
title: PyData Seattle 2017 talk
modified: 2017-07-07
---

I gave a talk entitled ["Building a community fountain around your data stream"](https://pydata.org/seattle2017/schedule/presentation/99/) at the PyData Seattle 2017 Conference held at Microsoft on July 7th.

You can [watch it here on Microsoft's channel](https://channel9.msdn.com/Events/PyData/Seattle2017/BRK09) or on [youtube](https://www.youtube.com/watch?v=Co8XiL6242I) or view [my slides](https://mtpatter.github.io/talks/pydata-2017/).

Summary:

> The increasing availability of real-time data sources and the Internet of Things movement have pushed data analysis pipelines towards stream processing. But what does this really mean for my applications, and how do I have to change my code and workflow? In a new era of “Kappa architecture,” it’s easier than ever to use the same programming model for both batch and stream processing.

> For those interested in the design and operations side, I will cover high-level design considerations for architecting a modular and scalable stream processing infrastructure that can support the flexibility of different use cases and can welcome a community of users who are more familiar with batch processing. For the fast-batching Pythonistas, I’ll talk about some of the advantages of using streaming tech in a data processing pipeline and how to make your life easier with 1) built-in replication, scalability, and stream “rewind” for data distribution with Kafka, 2) structured messages with strictly enforced schemas and dynamic typing for fast parsing with Avro, and 3) a stream processing interface that is similar to batch with Spark that you can even use in a Jupyter notebook. When you’re ready to jump into the stream, or at least take a drink from the fountain, I’ll point you to an open source, containerized (with Docker), streaming ecosystem testbed that you can deploy to mock a stream of data and take your streaming analytics on a dry run over an astronomical data stream.


Speaker bio:

> After earning a PhD in astronomy, Maria Patterson spent several years at the University of Chicago’s Center for Data Intensive Science, where she worked on cloud-based pipelines for automated analysis of NASA satellite imagery and architectures for interdisciplinary scientific “data commons”. During the initial stages for NOAA’s move to the cloud with the Big Data Project, Maria worked with the Open Commons Consortium to ensure the interests of the academic and scientific community were represented. She is currently a Research Scientist at the University of Washington, working on scientific data pipelines for managing streams of real-time data from large-scale astronomy projects, including the Zwicky Transient Facility (ZTF) and the Large Synoptic Survey Telescope (LSST). Maria is passionate about open science, diversity in computing, and making everyone’s life easier through tech and was recently named a modern hidden figure in STEM in PepsiCo and 21st Century Fox’s “Search for Hidden Figures.”
