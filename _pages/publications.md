---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


<ol><li>Abhisek Samanta, Kedar Damle, Rajdeep Sensarma, <em>Tracking the many-body localized to ergodic transition via extremal statistics of entanglement eigenvalues</em>, <a href="https://journals.aps.org/prb/abstract/10.1103/PhysRevB.102.104201"> PRB Phys. Rev. B 102, 104201 (2020)</a></li>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
