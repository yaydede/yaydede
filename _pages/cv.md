---
layout: archive
title: "Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

|                         |                                      |
|:----------------------- |--------------------------------------|
| December 2015 | Ph.D., Cognitive and Information Sciences<br>University of California, Merced|

## Employment

|                         |                                      |
|:----------------------- |--------------------------------------|
| August 2018 (*to begin*) | Assistant Professor<br>Department of Psychological Sciences<br>University of Connecticut|
| August 2016 - *present* | Moore-Sloan Data Science Fellow<br>Berkeley Institute for Data Science<br>University of California, Berkeley|
| January 2016 – *present* | Postdoctoral Scholar<br>Institute of Cognitive and Brain Sciences<br>University of California, Berkeley|

## Peer-Reviewed Journal Publications
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## Refereed Conference Proceedings
{% for post in site.proceedings reversed %}
  {% include archive-single.html %}
{% endfor %}
