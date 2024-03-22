---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}

{% for post in site.research reversed %} {% assign sortedPosts = site.research | sort:'order' %}
{% include archive-single-research.html %} {% endfor %}

**Published Papers** 
test 3
{% for post in site.research reversed %} 
{% include archive-single-research.html %} {% endfor %}


**Working Papers**

{% include base_path %}
{% for post in site.research_wp reversed %}
  {% assign sortedPosts = site.research_wp | sort:'order' %}  
  {% include archive-single-research.html %}
{% endfor %}

**Work in Progress**
{% for post in site.research_winp reversed %}
  {% assign sortedPosts = site.research_winp | sort:'order' %}  
  {% include archive-single-research.html %}
{% endfor %}
