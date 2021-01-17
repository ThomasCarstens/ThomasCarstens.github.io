---
layout: single
title: "Data visualizations for COVID in South Africa"
excerpt: "Handin for the DVIC Data Visualisation Course, Dec '20."
header:
  teaser: /assets/images/posts/covid-data-viz/police.png
  overlay_image: /assets/images/posts/covid-data-viz/police.png

categories: Project

tags:
- Data visualisation

tags:
toc: true
toc_sticky: false
date: 2021-01-17
gallery:
  - image_path: /assets/images/posts/covid-data-viz/scatter_deaths.png
    alt: " Deaths in South Africa due to Covid-19 over December 2020"
    title: "Deaths in South Africa due to Covid-19 over December 2020"


gallery2:
  - image_path: /assets/images/posts/covid-data-viz/police.png
    alt: "Police in the streets of "
    title: "Subject categories, Try 2"
    - image_path: /assets/images/posts/covid-data-viz/military_covid.png
      alt: "Police in the streets of "
      title: "Subject categories, Try 2"
---
# Is there evidence that mobility affects surges in COVID infection?

{% include gallery id="gallery" caption="Was the military presence worth it?" %}

My statistical analysis links up human mobility in South Africa to surges in infection.  I wish to have a data-driven idea whether significant human movement affects Covid infections significantly. Using the Google Mobility Reports, I will be comparing the spikes in Virus infections to human movement in South Africa between 1 December 2020 and 29 December 2020.

## Deaths in South Africa due to Covid-19 over December 2020

{% include gallery id="gallery" caption="Data from 2019-nCoV Data Repository and Dashboard for South Africa" %}

My hypothesis H0 is: there is no significant correlation between human movement and virus propagation in South Africa of such period.

## Mobility Trends for South Africans over December 2020

<div class="flourish-embed flourish-chart" data-src="visualisation/4990512" ><script src="https://public.flourish.studio/resources/embed.js"></script></div>

This analysis is done on a national level, and seen the incubation time for the virus is roughly 10 days, the15 days prior to infection are examined for significant levels of human movement. Said otherwise, for each significant level of infection, we determine how often over 15 days the movement exceeded set bounds (in number of days). This information will be analysed in a final Poisson curve to determine if the spikes are in fact correlated or they are two random patterns.

<strong># TEMPORARY</strong>
- Covid infections are analysed according to the gradient in the number of infections as a rough measure of infectability. Significant levels of infection are those that cross a certain threshold in gradient.

- The nature of our location-tracking data is percentage according to a baseline. Therefore significant levels of movement could roughly be determined if it exceeds set bounds on a normal curve according to data available for South Africa.  

<strong># TEMPORARY</strong>

<div class="flourish-embed flourish-scatter" data-src="visualisation/4990187"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

{% include gallery id="gallery" caption="Was the military presence worth it?" %}

#Bibliography

Datasets: WHO information was not sufficient, more SA info here:
https://github.com/dsfsi/covid19za
