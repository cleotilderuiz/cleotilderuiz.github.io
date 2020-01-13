---
layout: post
title: MTA Turnstile Analysis
---

Increasing attendees for Women Tech Women Yes Annual Gala. 

Working with my collegueas, Anu G and Dimiter M, we have analyzed MTA Turnstile data for analysis of optimal locations where email signups can be solicited.

-----

### Objectives

We wanted to minimize the "noise" in data. By reducing tourists sign up and maximizing resident commuters.

## Methodology

MAT Turnstile data is available [here](http://web.mta.info/developers/turnstile.html) and updated weekly. The data is not "clean" and does need standardization (see list below).

* remove duplicates
* removing faulty turnstile data
* formatting fields
* creating formulas to estimate actual entries and exits

Once the data is cleaned then we began to look at the top stations.

![Image test]({{ site.url }}/images/Top5Stations.JPG)

Although these stations are the top 5 they do not tell the entire story. We know that those stations are in downtown and not encompassing the entire city.

![Image test]({{ site.url }}/images/Top5NYC.JPG)

## Recommendations
However if we base our methodology to include top stations by regions then Women Tech Women Yes should take the approach of targetting the stations below.

![Image test]({{ site.url }}/images/HotSpots.JPG)
