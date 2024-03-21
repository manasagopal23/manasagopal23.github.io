---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}

**Published Papers** 

{% for post in site.researchpub reversed %}
  {% assign sortedPosts = site.researchpub | sort:'order' %}  
  {% include archive-single-research.html %}
{% endfor %}

**Working Papers**
{% for post in site.research_wp reversed %}
  {% assign sortedPosts = site.research_wp | sort:'order' %}  
  {% include archive-single-research.html %}
{% endfor %}

**Work in Progress**
{% for post in site.research_winp reversed %}
  {% assign sortedPosts = site.research_winp | sort:'order' %}  
  {% include archive-single-research.html %}
{% endfor %}
