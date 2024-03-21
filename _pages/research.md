---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}

**Published Papers** 

{% for post in site.research reversed %}
  {% assign sortedPosts = site.research | sort:'order' %}  
  {% include archive-single-research.html %}
{% endfor %}

