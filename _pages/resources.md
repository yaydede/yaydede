---
layout: archive
title: "Community resources"
permalink: /resources/
author_profile: true
---

{% include base_path %}

Here are a few

{% for post in site.resources reversed %}
  {% include archive-resource.html %}
{% endfor %}
