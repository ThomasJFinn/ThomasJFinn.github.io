---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

My research interests revolve around understanding the large-scale behaviour of strongly correlated random systems.

## Publications

F., Stauffer, [Non-equilibrium multi-scale analysis and coexistence in competing first-passage percolation](https://ems.press/journals/jems/articles/8736482), Journal of the European Mathematical Society

F., Stauffer, [Coexistence in competing first-passage percolation with conversion](https://projecteuclid.org/journals/annals-of-applied-probability/volume-32/issue-6/Coexistence-in-competing-first-passage-percolation-with-conversion/10.1214/22-AAP1792.short), Annals of Applied Probability

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
