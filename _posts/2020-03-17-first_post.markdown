---
layout: post
title:  "Keep Track of the Curve"
date:   2020-03-17 13:17:00 +0530
---


## Goal
Coronavirus cases have been increasing exponentially in the US. In order to get a better understanding of this awful phenomenon, we have decided to post a daily plot of cumulative confirmed cases.

While there are many metrics that one can follow, cumulative cases is particularly informative:

* It is a strong indicator of the _speed_ of virus transmission
* We can compare these metrics across countries
* If it becomes _less_ exponential, it means that containment efforts are somewhat helping

## Data
Confirmed case data is curated by a team at Johns Hopkins University here: [https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases](https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases)

The data can be fit with an exponential curve to estimate future cumulative cases:

![hello]({{ site.baseurl }}/assets/plots/2020-3-16-US2.png)
