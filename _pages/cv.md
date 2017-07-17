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
Ph.D., Cognitive and Information Sciences
<br>University of California, Merced
<br>December 2015

## Employment
<table>
<colgroup>
<col width="40%" />
<col width="60%" />
</colgroup>
<tbody>
<tr>
<td markdown="span" valign="top">August 2018</td>
<td markdown="span" valign="top">Assistant Professor</td>
</tr>
<tr>
<td markdown="span" valign="top">(*to begin*)</td>
<td markdown="span" valign="top">Department of Psychological Sciences</td>
</tr>
<tr>
<td markdown="span" valign="top"></td>
<td markdown="span" valign="top">University of Connecticut</td>
</tr>
</tbody>
</table>

August 2018
<br>Assistant Professor
<br>Department of Psychological Sciences
<br>University of Connecticut

August 2016 – *present*
<br>Moore-Sloan Data Science Fellow
<br>Berkeley Institute for Data Science
<br>University of California, Berkeley

January 2016 – *present*
<br>Postdoctoral Scholar
<br>Center for Data on the Mind
<br>Institute of Cognitive and Brain Sciences
<br>University of California, Berkeley

## Peer-Reviewed Journal Publications
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## Refereed Conference Proceedings
{% for post in site.proceedings reversed %}
  {% include archive-single.html %}
{% endfor %}
