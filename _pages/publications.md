---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Workshop Papers

_[ICML Compbio Workshop]_ **Dmitrii Gavrilev**, Nurlybek Amangeldiuly, Sergey Ivanov, Evgeny Burnaev. "[High Performance of Gradient Boosting in Binding Affinity Prediction](https://arxiv.org/pdf/2205.07023.pdf)." (2022)