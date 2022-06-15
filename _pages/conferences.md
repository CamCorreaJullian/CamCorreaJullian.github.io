---
layout: archive
title: "Conference Proceedings"
permalink: /conferences/
author_profile: true
---

{% for post in site.conferences reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
