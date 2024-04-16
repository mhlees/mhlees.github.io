---
layout: page
title: Data Sensitivity
description: 
img: assets/img/ramifications.jpg
importance: 3
category: ongoing
---

Computational modelling and simulation provide a unique way to reason about the natural world. Often physical
and social systems are abstracted into mathematical equations that describe processes at multiple spatial and
temporal scales [Hoekstra et al 2014]. The advent of multi-scale modelling has enabled scientists to study holistic systems, where processes at the micro-scale are coupled to macro-scale processes by mapping inputs of one model the outputs of another. While progress has been made in the natural sciences there are still hard limits set by the computational requirements of these systems (e.g., blood flow) and currently, these techniques are not common place in computational social science (or computational psychology).
Over the last two decades the world has seen has seen an explosive growth in the amount of data that is recorded
about societies [Ball 2012]. This has been followed with a growth in the field of computational social science and
computational models of socio-economic systems. These new data sets provide, for the first time, a way to
capture, abstract and validate models regarding individual human behavior and the associated collective behavior
(e.g., mobility [KP 3], social systems [KP 4]). However, the scale of these models is typically limited by the
computational demands and issues related to sensitivity (and privacy) of the associated datasets. Combining
models that rely on multiple data sources at multiple scale may lead to unpredictable ramifications in terms of
privacy, uncertainty and subsequent validity.
In this proposal we plan to develop algorithms that provide ways to reason about (specifically but not solely) socio-health systems. By abstracting multi-scale models to data flow graphs [Moreau &amp; Groth 2013; Groth et al 2009]we aim to provide a novel methodology and associated methods to help modelers reason about large-scale holistic systems in a way that makes both the challenges of privacy and uncertainty transparent. The vision is one in which models are considered as &quot;black box&quot; data generator (nodes) in a data flow graph. In general, the nodes in the data
flow graph can be models that generate output data, or they can simply be real world data sets (from longitudinal
studies, or demographic data - e.g., CBS). The edges then describe flows from data to models, and prescribe
guarantees on the data, in terms of scale (spatial, temporal), format, privacy constraints and uncertainty and error.
By examining the data flow graph and data descriptors, this project will look at ways to rapidly characterize both
model generated data and real data in terms of enumerated sets of ramifications. Moreover, given the
computational cost of running large-scale models, the data flow graphs provide an important abstraction that can
allow modelers to reason about these potential ramifications without the cost of execution.
Research Question
The core research question is:
- To what extent can we use data flow graphs be used to reason the ramifications of large multi-scale
models, and is it possible to develop ways to capture privacy and uncertainty into the data flow
framework.
From a computational science perspective this research will address fundamental modelling questions in an area
that still has significant challenges. While model abstraction formalisms have been developed before (e.g., DEVS

[Concepcion &amp; Zeigler 1988]) there applicability to the socio-economic (health) domain has been limited by their
inability to deal with privacy and uncertainty. The key challenges will be how to conceptualize classical multi-scale
modelling challenges (e.g., uncertainty quantification, sensitivity) into the new data flow paradigm. Finally, the
data flow graphs provide a natural way to develop executable models through translation to system dynamic
descriptions [Forrester 1994]. The research will explore techniques for mapping data flow graphs to system
dynamics models.
From a data provenance and computational workflow perspective, this moves beyond just capturing and querying
provenance (i.e. the data flow graph) to sophisticated analytics on the graph. In particular, this provides an
important environment for examining heterogeneous data flow graphs stemming from multiple applications and
domains. This project also aims to experiment with the relationship between past executions and prospective
executions. Lastly, the relationship between data description and data flow graphs is under explored and a
trajectory for this work.