---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

* Regional labour demand effects of decarbonisation in EU regions: A Spatial Computable General Equilibrium Analysis
      ** Sacha den Nijs & Dr. Olga Ivanova (PBL)
      ** Working paper

* Clean Technology Adoption and Skill Sorting
      ** Sacha den Nijs & Stefanos Tyros (VU) 
      ** Working paper

* Regional competitive opportunities of fossil fuel cost changes and the role of decarbonization
      ** Sacha den Nijs & Mark Thissen (PBL) 
      ** Work in progress


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
