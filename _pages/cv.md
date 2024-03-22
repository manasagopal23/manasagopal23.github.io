---
layout: archive
title: "Published Papers"
permalink: /cv/
author_profile: true
---
{% include base_path %}
{% for post in site.portfolio reversed %} 
{% include archive-single-research.html %} 
{% endfor %}

