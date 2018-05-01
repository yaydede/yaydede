---
layout: archive
title: "Researcher resources"
permalink: /resources/
author_profile: true
---

{% include base_path %}

{% for post in site.researcher_resources reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
