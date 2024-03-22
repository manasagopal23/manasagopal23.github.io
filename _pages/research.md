---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}

{% for post in site.research reversed %} {% assign sortedPosts = site.research | sort:'order' %}
{% include archive-single-research.html %} {% endfor %}

**Publications**
{% for post in site.researchpub reversed %} {% assign sortedPosts = site.researchpub | sort:'order' %}
{% include archive-single-research.html %} {% endfor %}
