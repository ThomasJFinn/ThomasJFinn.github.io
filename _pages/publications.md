---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

My research interests revolve around understanding the large-scale behaviour of strongly correlated random systems.

My work investigates phase transitions in processes that lack the properties typically required for a rigorous analysis. For example, often one requires stationarity and monotonicity to prove meaningful statements. Even processes that are straightforward to define can lack these properties and mathematicians have long sought robust techniques that can handle them. Building on the techniques of [Sidoravicius and Stauffer](https://link.springer.com/article/10.1007/s00222-019-00890-5) in collaboration with Alexandre Stauffer, I built a refined multi-scale argument to handle non-equilibrium random processes and applied it to the challenging problem of coexistence in competing first-passage percolation.

In my current position as a postdoctoral researcher at Durham University, I work with Sunil Chhita to investigate the rough-smooth boundary in the two-periodic Aztec diamond. Domino tilings of the Aztec diamond have provided some of the most mathematically rich results in statistical physics over the last three decades and the two-periodic Aztec diamond observes a fascinating phase transition between rough and smooth regions.

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
