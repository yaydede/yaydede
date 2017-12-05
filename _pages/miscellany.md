---
layout: archive
title: "Miscellany"
permalink: /miscellany/
author_profile: true
---

{% include base_path %}

## Supplementary materials for researchers

{% for post in site.supplementary reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## Resources and support

{% for post in site.researcher_resources reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
