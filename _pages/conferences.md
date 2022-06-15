---
layout: archive
title: "Conference Proceedings"
permalink: /conferences/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=EXXGXOYAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
 
{% for post in site.conference reversed %}
  {% include archive-single.html %}
{% endfor %}
