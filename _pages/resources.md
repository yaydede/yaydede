---
layout: archive
title: "Community resources"
permalink: /resources/
author_profile: true
---

{% include base_path %}

Here are a few of the community resources that I've helped develop. Click on
the project description to check out the resource. Additional information
related to the project are available in the thumbnails below the description,
including open-access publications or preprints
(<i class="ai ai-fw ai-open-access-square"></i>),
non-OA publications (<i class="fa fa-file-pdf-o" aria-hidden="true"></i>;
available for *personal use only*), GitHub repositories
(<i class="fa fa-github" aria-hidden="true"></i>), OSF projects
(<i class="ai ai-fw ai-osf"></i>), and miscellaneous information (<b>∼</b>).

{% for post in site.resources%}
  {% include archive-resource.html %}
{% endfor %}
