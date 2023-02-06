---
title: Intro to RSA with R
tags: [statistics, R]
style: fill
color: primary
description: As our new project is planning on an RSA analysis, I'm also learning about it now.
---

The Representational Similarity Analysis (RSA) is a statisticl analysis proposed by [Kriegeskorte, Mur, and Bandettini (2008, Frontiers in System Neuroscience)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2605405/). Here's also a Youtube video of [his presentation at Dartmouth](https://www.youtube.com/watch?v=_-D4S0x5AFc&t=2921s&ab_channel=Dartmouth) talking about using RSA to analyze visual-object population codes.

As far as I am concerned, I think the most beneficial function of RSA is that it allows comparison between data collected through different modules. For example, our project aims to simultaniously collect real-time record of behavioral performance (percentage of correct answers), brain imaging signal(EEG), and biological signal(eye-tracking). As data from these modules are encoded in different ways it could be difficual to directly compare them all together. However, the RSA analyzes second-order isomorphisms, that is to say, it captures how similar a measure is to itself and also compare a measure with another, and in this way, we by-pass the origical data format and focus on a more representational level of information contained within the data. We compare this representation across different modules, so as to reach different research goals.

RSA is widely used in fMRI studies, but it can also be applied to a variety of other imaging modalities, including MEG and EEG. It is widely used in cognitive neuroscience to test hypotheses about how different mental processes are represented in the brain and how these representations change with development, aging, or in response to interventions such as training or injury.

On Github, I found [a handy tutorial](https://github.com/markallenthornton/MIND18_RSA_tutorial) introducing the details of conducting RSA with R. Along with this file is [a Youtube video of MIND summer school](https://www.youtube.com/watch?v=ufGtuT_J75w&t=144s&ab_channel=MINDSummerSchool) teaching the contents.

I'll update more about this topic later.