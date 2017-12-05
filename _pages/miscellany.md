---
layout: archive
title: "Miscellany"
permalink: /miscellany/
author_profile: true
---

{% include base_path %}

## Supplementary materials for researchers

{% for post in site.supplementary reversed %}
  {% include archive-single.html %}
{% endfor %}

## Resources and support

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
