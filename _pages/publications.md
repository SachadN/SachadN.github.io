---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

* Regional labour demand effects of decarbonisation in EU regions: A Spatial Computable General Equilibrium Analysis
     * Sacha den Nijs & Dr. Olga Ivanova (PBL)
     * Working paper

* Clean Technology Adoption and Skill Sorting
    * Sacha den Nijs & Stefanos Tyros (VU) 
    * Working paper

* The energy efficiency gap and barriers to investments: evidence from the Netherlands
    * Sacha den Nijs, Leon Bremer (VU), Prof. Dr. Henri de Groot (VU) 
    * Working paper

* Regional competitive opportunities of fossil fuel cost changes and the role of decarbonization
    * Sacha den Nijs & Dr. Mark Thissen (PBL Netherlands Environmental Assessment Agency) 
    * _Work in progress_


---
Policy Papers
===== 

* Weterings, A., Bakens, J., Ivanova, O., den Nijs, S., Thissen, M., Abbink, H., & Bijlsma, I. (2022). Inzicht in arbeidsmarktknelpunten voor de uitvoering van het klimaatbeleid. Available <u><a href="https://www.pbl.nl/publicaties/inzicht-in-arbeidsmarktknelpunten-voor-de-uitvoering-van-het-klimaatbeleid">here</a>.</u>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
