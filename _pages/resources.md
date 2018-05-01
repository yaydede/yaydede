---
layout: archive
title: "Community resources"
permalink: /resources/
author_profile: true
---

{% include base_path %}

{% for post in site.resources reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
