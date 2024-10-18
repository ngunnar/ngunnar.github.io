---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

 About me
======
Currently an industrial Ph.D student at Uppsala University and the radiotherapy company Elekta Instrument AB. My research is about motion modeling for medical image sequences, so-called intra-intervetional medical images. Such sequences often suffers from sparse temporal and spatial resolutions. By modeling the dynamics we aim to estimate the motions in unobserved states, like forecasting and interpolation between observed images in time, and extrapolation to spatially unobserved positions.

 Background
======

- **2018 - today:** Ph.D Machine Learning, Uppsala University
- **2018 - 2022:** Lic. of Philosophy, EE with Specialisation in Signal Processing, Uppsala University
- **2015 - 2018:** Software developer, RaySearch Instrument AB
- **2013 - 2016:** Software developer, Sectra AB
- **2008 - 2013:** M.Sc. in Engineering Phyics, Uppsala University
- **1987:** Born

Upcoming events
======

<ul>{% for post in site.talks %}
    {% if post.date > site.time %}
      {% include archive-single-listitem.html %}
    {% endif %}    
  {% endfor %}</ul>

 Past events
======

<ul>{% for post in site.talks reversed %}
    {% if post.date <= site.time %}
      {% include archive-single-listitem.html %}
    {% endif %}    
  {% endfor %}</ul>
