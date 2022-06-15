---
layout: archive
title: "Conference Proceedings"
permalink: /conferences/
author_profile: true
---
{% include base_path %}

{% for post in site.conferences reversed %}
  {% include archive-single.html %}
{% endfor %}
