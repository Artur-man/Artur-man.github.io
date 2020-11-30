---
layout: archive
title: "Research Interests:"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

My primary research interest is focused on implementing and designing machine learning algorithms for biomedical inference and data integration that lead to the development of software tools with reusable and robust data analysis pipelines, and I am also interested in various informatics tools for developing these software platforms that help researchers discover crucial biomedical knowledge.

My research interests are also lie in Statistical Machine Learning on Networks with applications to Biological Networks and Knowledge Graphs. 

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
