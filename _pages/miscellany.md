---
layout: archive
title: "Supplementary materials"
permalink: /miscellany/
author_profile: true
---

{% include base_path %}

Here's some additional information from various publications. Click on the
relational operator (<b>∼</b>) to access the additional
information. Links to the relevant paper (either open-access
<i class="ai ai-fw ai-open-access-square"></i> or not
<i class="fa fa-file-pdf-o" aria-hidden="true"></i>; provided for **personal
use only**) are given. Where applicable, links to GitHub repositories
(<i class="fa fa-github" aria-hidden="true"></i>) and OSF projects
(<i class="ai ai-fw ai-osf"></i>) that were instrumental in the related
material are also provided.

{% for post in site.miscellany %}
  {% include archive-single-cv.html %}
{% endfor %}
