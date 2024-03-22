---
layout: archive
title: "Published Papers"
permalink: /researchpub/
author_profile: true
---
{% include base_path %}

{% for post in site.researchpub reversed %} {% assign sortedPosts = site.researchpub | sort:'order' %}
{% include archive-single-research.html %} {% endfor %}
