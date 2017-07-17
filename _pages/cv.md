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

<!-- |                         |                                      |
|:----------------------- |--------------------------------------|
| December 2015 | Ph.D., Cognitive and Information Sciences<br>University of California, Merced| -->

December 2015
<br>Ph.D., Cognitive and Information Sciences
<br>University of California, Merced

## Employment

|                         |                                      |
|:----------------------- |--------------------------------------|
| August 2018 (*to begin*) | Assistant Professor<br>Department of Psychological Sciences<br>University of Connecticut|
| August 2016 - *present* | Moore-Sloan Data Science Fellow<br>Berkeley Institute for Data Science<br>University of California, Berkeley|
| January 2016 – *present* | Postdoctoral Scholar<br>Institute of Cognitive and Brain Sciences<br>University of California, Berkeley|

## Peer-Reviewed Journal Publications

Mentees’ names underlined. Asterisk indicates dual first-author position. Open access articles (<i class="ai ai-fw ai-open-access-square" aria-hidden="true"></i>) are linked below; all other PDFs (<i class="fa fa-file-pdf-o" aria-hidden="true"></i>) are provided for **personal use only.** Supplementary materials on GitHub (<i class="fa fa-github" aria-hidden="true"></i>) and OSF (<i class="ai ai-fw ai-osf-square" aria-hidden="true"></i>) for each publication are linked below the citation.

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## Refereed Conference Proceedings

Mentees’ names underlined. Asterisk indicates dual first-author position. Open access articles (<i class="ai ai-fw ai-open-access-square" aria-hidden="true"></i>) are linked below; all other PDFs (<i class="fa fa-file-pdf-o" aria-hidden="true"></i>) are provided for **personal use only.** Supplementary materials on GitHub (<i class="fa fa-github" aria-hidden="true"></i>) and OSF (<i class="ai ai-fw ai-osf-square" aria-hidden="true"></i>) for each publication are linked below the citation.

{% for post in site.proceedings reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
