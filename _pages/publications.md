---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


<ol><li>A. Samanta. <a href="https://journals.aps.org/prb/abstract/10.1103/PhysRevB.102.104201">name of the paper.</a><em> PRB</em> Phys. Rev. B 102, 104201 – Published 2 September 2020</li>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
