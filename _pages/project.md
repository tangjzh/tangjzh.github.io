---
layout: archive
permalink: /project/
title: "Projects"
author_profile: true
redirect_from: 
  - /pj/
  - /project.html
---

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single-project.html %}
{% endfor %}
