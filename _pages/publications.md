---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

## PhD Research


## Undergraduate Research
* "Pricing and Capacity Allocation: Implications for Manufacturers with Product Sharing." with Bin Dai. *Naval Research Logistics* 2020, 67(3): 201-222. [[Document](https://YuNu1210.github.io/files/NRL_ProductSharing.pdf)]


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
