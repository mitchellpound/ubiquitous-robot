---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}

  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

## Publications

- P. Crooks, X. Gao, M. Pound, and C. Thompson, Some incarnations of Hamiltonian reduction in symplectic geometry and geometric representation theory, Springer INdAM volume for "Poisson 2024" (to appear).
  [arXiv link](https://arxiv.org/abs/2503.23636)
- M. Pound, S. Clemens, T. Brough, P. Jahangiry, and J. Goodridge, Bruno: A Julia package for simulation, financial asset pricing and delta hedging, Journal of Open Source Software 8 (2023), no. 82, 5056.
  [journal link](https://joss.theoj.org/papers/10.21105/joss.05056)
- A. C. Romney, C. J. Hartwell, J. T. Harrison, and M. Pound, _The Loki equipment exercise part 2: Crisis management_. Management Teaching Review 9 (2024), no. 2, 158–174.
  [journal link](https://journals.sagepub.com/doi/full/10.1177/23792981221089277)
- A. C. Romney and M. Pound, Pivoting at the midpoint: How midpoint course adjustments influence student engagement, Journal on Empowering Teaching Excellence 5 (2021), no. 1, 5.
  [journal link](https://digitalcommons.usu.edu/jete/vol5/iss1/5/)

## Preprints

Future pre-prints to come!

{% include base_path %}

<!-- Good for once you make each one an individual page... later -->
<!-- New style rendering if publication categories are defined -->

<!--
{% if site.publication_category %}
{% for category in site.publication_category  %}
{% assign title_shown = false %}
{% for post in site.publications reversed %}
{% if post.category != category[0] %}
{% continue %}
{% endif %}
{% unless title_shown %}

<h2>{{ category[1].title }}</h2><hr />
{% assign title_shown = true %}
{% endunless %}
{% include archive-single.html %}
{% endfor %}
{% endfor %}
{% else %}
{% for post in site.publications reversed %}
{% include archive-single.html %}
{% endfor %}
{% endif %}
-->
